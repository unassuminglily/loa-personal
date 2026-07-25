# Lily Ofori-Amanfo — static portfolio

A framework-free portfolio for GitHub Pages.

## Structure

```text
site/
├── index.html
└── assets/
    ├── css/styles.css
    ├── images/hero.jpg
    └── js/main.js
```

## Edit content

- Text and links: edit `index.html`
- Colours and layout: edit `assets/css/styles.css`
- Project filtering and mobile menu: edit `assets/js/main.js`
- Hero image: replace `assets/images/hero.jpg` and keep the same filename

To add a project, duplicate a `<article class="project-card">` block. Set its
`data-category` to one or more of `web`, `writing`, or `concept`.

## Preview locally

Open `index.html` directly, or serve the `site` folder with any simple local
web server.

## Publish on GitHub Pages

The simplest approach is to place the contents of `site` at the root of a
repository and enable Pages from the repository's default branch in
**Settings → Pages**.

No build command, package installation, CMS, or environment variables are
required.
