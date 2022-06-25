# Projeto de tradução do livro de bolso "O guia NewBee para fazer hidromel"

O conteúdo do livro está em arquivos markdown localizados na pasta `docs`, utilizando a ferramenta Docusaurus para gerar as páginas disponíveis em: https://lucashilles.github.io/mead-guide/

-----
## Website

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
