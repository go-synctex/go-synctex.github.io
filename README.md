<p align="center"><img src="https://raw.githubusercontent.com/go-synctex/brand/main/social/go-synctex.png" alt="go-synctex/go-synctex.github.io" width="720"></p>

# go-synctex.github.io

The organization's institutional landing page, served at
<https://go-synctex.github.io> and built with [Hugo](https://gohugo.io). It is a
single page (custom `layouts/index.html`, capability cards driven by
`[[params.phases]]` in `hugo.toml`).

Documentation lives in a separate repository,
[go-synctex/docs](https://github.com/go-synctex/docs), served at
<https://go-synctex.github.io/docs/>. This page links there.

`.github/workflows/deploy-pages.yml` builds the landing with Hugo and deploys it
to GitHub Pages on every push to `main`.

## Local preview

```bash
hugo server      # http://localhost:1313
```
