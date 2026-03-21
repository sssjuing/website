## Local Development

Pre-requisites: [Hugo](https://gohugo.io/getting-started/installing/), [Go](https://golang.org/doc/install) and [Git](https://git-scm.com)

```shell
# Start the server
hugo server --buildDrafts --disableFastRender
```

## Create New Page

Create new document.

```shell
hugo new content/docs/_index.md
```

Create new article.

```shell
hugo new content/articles/_index.md
```

### Update theme

To update all Hugo modules in your project to their latest versions, run the following command:

```shell
hugo mod get -u
```

To update Hextra to the latest released version, run the following command:

```shell
hugo mod get -u github.com/imfing/hextra
```

If you want to try the most recent changes before the next release, update the module to the development branch directly (⚠️ may contain unstable/breaking changes):

```shell
hugo mod get -u github.com/imfing/hextra@main
```

See [Update modules](https://gohugo.io/hugo-modules/use-modules/#update-modules) for more details.

## Deployment

See [Deploy Site](https://imfing.github.io/hextra/docs/guide/deploy-site/) for more details.
