# kalmas.net

Project to build and deploy to https://kalmas.net as Github Page. Made with [Hugo](https://gohugo.io/) and [Lynx](https://github.com/jpanther/lynx).

```sh
# run for local dev
hugo server

# build for release
hugo --gc --minify --baseURL 'https://kalmas.net/'
```

To launch [deploy workflow](/.github/workflows/hugo.yaml) push to `main` branch.
