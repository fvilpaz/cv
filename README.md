# Fernando Vilas Paz — Interactive CV

Single-file HTML curriculum vitae with three interactive modes, built without frameworks.

**Live →** [fvilpaz.github.io/cv](https://fvilpaz.github.io/cv)

---

## Interactive features

| Feature | How |
|---------|-----|
| **EN / ES language toggle** | JS — swaps all body text between English and Spanish |
| **Dark / light mode** | JS + CSS custom properties — persists SVG icon state |
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
