# interfaith-sanctuary.org

A single, self-contained static website. All HTML, CSS, and JavaScript are inlined in `index.html`. There is no build step, package manager, dependency install, lint, or test suite.

## Cursor Cloud specific instructions

- Static site, no dependencies to install. Python 3 and Node are preinstalled; nothing is needed to develop or run it.
- Run locally with a static file server from the repo root: `python3 -m http.server 8000`, then open `http://localhost:8000/`.
- The entry file is `index.html`.
- The page uses client-side i18n (a language selector re-renders text without a page reload).
- "Building" just means opening the static file in a browser; there is no lint or automated test tooling.
