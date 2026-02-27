# AGENTS.md

## Cursor Cloud specific instructions

This is a zero-dependency, single-file static HTML application (`index.html`). There is no build system, package manager, linter, test framework, or backend.

### Running the application

Serve the file with any static HTTP server:

```
python3 -m http.server 8080
```

Then open `http://localhost:8080/index.html` in Chrome.

### Key notes

- The entire application lives in `index.html` (inline CSS + JS).
- There are no automated tests, no linting tools, and no build step.
- No dependencies to install; the update script is a no-op (`echo "No dependencies to install"`).
