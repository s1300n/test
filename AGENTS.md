# AGENTS.md

## Cursor Cloud specific instructions

This is a minimal static HTML website with no build system, no dependencies, and no package manager.

### Running the site

Serve the files locally with Python's built-in HTTP server:

```
python3 -m http.server 8080 --directory /workspace
```

Then open `http://localhost:8080/` in a browser.

### Key facts

- There is no linting, testing framework, or build step.
- The entire project is two static HTML files (`index.html`, `index2.html`).
- No dependencies to install — the update script is a no-op (`true`).
