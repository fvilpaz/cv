<div align="right">
  <img src="https://img.shields.io/badge/EN-1a6fc4?style=flat-square" alt="English">
  &nbsp;<a href="README.es.md"><img src="https://img.shields.io/badge/ES-555555?style=flat-square" alt="Español"></a>
</div>

# Fernando Vilas Paz — Interactive CV

Single-file HTML curriculum vitae with three interactive modes, built without frameworks.

**Live →** [fvilpaz.github.io/cv](https://fvilpaz.github.io/cv)

---

## Interactive features

| Feature | How |
|---------|-----|
| **EN / ES language toggle** | JS — swaps all body text between English and Spanish |
| **Dark / light mode** | JS + CSS custom properties — SVG icon switches with the theme |
| **PDF export** | `window.print()` with `@media print` rules tuned for exactly 3 clean pages |

All three controls sit in a fixed bottom-right button bar. Buttons are hidden from the PDF output.

## Stack

| Layer | Tech |
|-------|------|
| Structure | HTML5 (semantic, single file) |
| Style | CSS3 — Grid, Flexbox, custom properties, `@media print` |
| Interactivity | Vanilla JS — no dependencies |
| Fonts | Bricolage Grotesque + Geist Mono (Google Fonts) |
| Hosting | GitHub Pages |

## File

Everything lives in `index.html` — including the profile photo as a base64 `data:` URI, so the CV is fully self-contained and works offline.
