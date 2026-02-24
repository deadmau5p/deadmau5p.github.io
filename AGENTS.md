# AGENTS

## Cursor Cloud specific instructions

This is a zero-dependency static HTML/CSS site (GitHub Pages landing page). There is no package manager, build step, linter, or test suite.

### Running the dev server

```bash
python3 -m http.server 4000
```

Then visit `http://localhost:4000`. See `README.md` for the same instruction.

### Key notes

- The only dynamic code is a one-line `<script>` in `index.html` that sets the copyright year.
- Google Fonts ("Space Grotesk") is loaded from a CDN; the page degrades gracefully without it.
- No lint, test, or build commands exist for this project.
