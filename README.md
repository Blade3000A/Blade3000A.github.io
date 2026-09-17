# Blade3000A — Quantum Software Portfolio

Source for the GitHub Pages site at **<https://blade3000a.github.io>**.

A single static page — no build step, no dependencies — listing selected work in
quantum machine learning, quantum cryptography, nonlocal games, and circuit
optimization, with links to each project repository.

## Contents

| File | Purpose |
| --- | --- |
| `index.html` | The whole site: markup and CSS in one file |
| `Blade3000A_Quantum_Developer_Portfolio.pdf` | The print version, linked from the footer |

## Editing

Edit `index.html` and push to `main` — GitHub Pages redeploys automatically,
usually within a minute. To preview locally, open the file in a browser, or:

```bash
python -m http.server 8000
```

then visit <http://localhost:8000>.

Each project is one `<li>` in the `.work` list: a category chip, a linked title,
a description, and the repository link. Copy an existing block to add another.
Colors are CSS custom properties defined once at the top of the `<style>` block,
with a dark-mode set under `prefers-color-scheme: dark`.
