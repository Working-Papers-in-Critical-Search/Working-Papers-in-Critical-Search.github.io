# Working-Papers-in-Critical-Search.github.io

This repository exists only to serve the **organization-root URL**:

> <https://working-papers-in-critical-search.github.io/>

Visiting the bare URL above redirects to the journal's main site at
<https://working-papers-in-critical-search.github.io/home/>.

Without this repository, the bare org URL would 404 — GitHub Pages serves
each project repo at its own subpath (`/home/`, `/paper-001-introduction/`,
etc.) and there is no default landing page at the root unless an
`<org>.github.io` repo exists.

The implementation is a single `index.html` with a `<meta http-equiv="refresh">`
tag plus a JavaScript fallback. No build step, no dependencies.

## When to update

- If the canonical journal URL ever moves off `/home/` (for example because
  we acquire a custom domain or rename the `home` repo to live at the org
  root directly), update the redirect target in `index.html`.
- Otherwise leave it alone.

## License

MIT for the redirect code; site content is governed by the
[main journal site](https://github.com/Working-Papers-in-Critical-Search/home).
