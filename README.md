# Zakaria Mzaouali — academic website

Source for [moorishqubit.github.io](https://moorishqubit.github.io), built with [Quarto](https://quarto.org/) and deployed with GitHub Pages.

## Local preview

```bash
quarto preview
```

## Build

```bash
quarto render
```

The rendered site is written to `_site/`. A GitHub Actions workflow rebuilds and deploys the site whenever `main` changes.

## Custom `.ma` domain later

After registering the domain, add a root-level file named `CNAME` containing only the chosen hostname, for example:

```text
mzaouali.ma
```

Then configure the same hostname under **Repository Settings → Pages** and point the registrar's DNS records to GitHub Pages. Update `website.site-url`, `robots.txt`, and the URLs in `assets/schema.html` at the same time.

