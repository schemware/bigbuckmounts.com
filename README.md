# bigbuckmounts.com

The coming-soon page for Big Buck Mounts, a taxidermy studio, served by GitHub Pages from `main` at https://bigbuckmounts.com. Static HTML and CSS: no build step, no framework and no Jekyll (`.nojekyll`).

- `index.html`: the coming-soon page.
- `styles.css`: styles, with light and dark colour schemes that follow the visitor's system setting.
- `images/favicon.svg`: the antler-and-plaque mark as a favicon. The same drawing is inline in `index.html`.
- `CNAME`: the custom domain for GitHub Pages.

Paths in the pages are relative, so the site also previews by opening `index.html` directly or from any static server (for example `python3 -m http.server`).

## DNS

Point the domain at GitHub Pages at the registrar:

- Four A records for `@`: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153.
- A CNAME for `www` → `schemware.github.io`.

Once DNS resolves, turn on "Enforce HTTPS" in the repository's Pages settings.
