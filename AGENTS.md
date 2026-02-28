## Cursor Cloud specific instructions

This is a static HTML/CSS personal blog with no build tools, no package manager, and no dependencies.

- **Dev server**: `python3 -m http.server 8080` from the repo root, then open `http://localhost:8080/index.html`
- **Structure**: `index.html` (homepage), `about.html` (about page), `posts/*.html` (blog posts), `style.css` (shared styles)
- **No lint/test/build**: There are no linters, test frameworks, or build steps configured. Validation is done by opening pages in a browser.
- **Adding a new post**: Create a new `.html` file in `posts/`, link it from `index.html`, and use `../style.css` for the stylesheet.
