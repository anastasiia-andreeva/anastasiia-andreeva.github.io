# anastasiia.andreeva.github.io

Personal academic website for Anastasiia Andreeva, built with [Hugo](https://gohugo.io) and deployed via GitHub Pages.

## Local development

Requires [Hugo (extended)](https://gohugo.io/installation/).

```bash
hugo server
```

Visit `http://localhost:1313`.

## Deployment

Pushing to `main` triggers `.github/workflows/deploy.yml`, which builds the site with Hugo and publishes it to GitHub Pages. Enable Pages once under Settings → Pages → Source: GitHub Actions.

## Updating content

See [UPDATING.md](UPDATING.md) for a plain-language guide to adding papers, updating the bio, and more.
