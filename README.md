# mehran-njz.github.io

Personal website built with [Docusaurus](https://docusaurus.io/).

Published at **https://mehran-njz.github.io/**

## Local development

```bash
npm install
npm start
```

Starts a local dev server at `http://localhost:3000/` with hot reload.

## Build

```bash
npm run build
```

Generates the static site into `build/`.

## Deployment

Deployment is automatic: pushing to `main` triggers the
[`Deploy to GitHub Pages`](.github/workflows/deploy.yml) workflow, which builds the
site and publishes it with GitHub Pages (source: **GitHub Actions**).

## Structure

| Path | Purpose |
| --- | --- |
| `docusaurus.config.js` | Main site configuration (title, URL, navbar, footer) |
| `sidebars.js` | Docs sidebar structure |
| `docs/` | Documentation pages |
| `blog/` | Blog posts |
| `src/` | React pages, components and CSS |
| `static/` | Static assets copied as-is to the site root |