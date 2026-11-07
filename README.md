# Editorial Research — Quarto Starter

A lightweight, monochrome research portfolio with serif headings, system sans-serif text, restrained monospace labels, and one muted blue accent.

## Preview

Open this folder in VS Code. From its terminal run:

```bash
quarto preview
```

Changes are reflected when saved. Stop preview with Ctrl+C.

## Adding this design to an existing site

1. Back up your existing `_quarto.yml` and `styles.css`.
2. Copy `styles.css` into your existing project directory.
3. In the existing `_quarto.yml`, ensure that `format: html: css: styles.css` is configured (maintain your own navbar and content pages).
4. If you want the included demo homepage, copy `index.qmd` **after backing up your own** and copy the other demo pages that its navigation uses.

For a completely separate preview, simply use this starter as its own Quarto project. No font services, images, or JavaScript are needed.

**Important:** In Quarto front matter, use `title: "..."` (a string), **not** `title: false`. The latter causes validation errors for page titles.
