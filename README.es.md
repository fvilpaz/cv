<div align="right">
  <a href="README.md"><img src="https://img.shields.io/badge/EN-555555?style=flat-square" alt="English"></a>
  &nbsp;<img src="https://img.shields.io/badge/ES-1a6fc4?style=flat-square" alt="Español">
</div>

# Fernando Vilas Paz — CV Interactivo

Currículum vitae en un único fichero HTML con tres modos interactivos, construido sin frameworks.

**Ver →** [fvilpaz.github.io/cv](https://fvilpaz.github.io/cv)

---

## Funcionalidades interactivas

| Función | Cómo |
|---------|------|
| **Selector de idioma EN / ES** | JS — cambia todo el texto del cuerpo entre inglés y español |
| **Modo oscuro / claro** | JS + variables CSS — el icono SVG cambia con el tema |
| **Exportar PDF** | `window.print()` con reglas `@media print` ajustadas para exactamente 3 páginas limpias |

Los tres controles están en una barra de botones fija en la esquina inferior derecha. Los botones quedan ocultos en el PDF.

## Stack

| Capa | Tecnología |
|------|-----------|
| Estructura | HTML5 (semántico, fichero único) |
| Estilos | CSS3 — Grid, Flexbox, custom properties, `@media print` |
| Interactividad | Vanilla JS — sin dependencias |
| Tipografías | Bricolage Grotesque + Geist Mono (Google Fonts) |
| Hosting | GitHub Pages |

## Fichero

Todo vive en `index.html` — incluida la foto de perfil como URI `data:` en base64, por lo que el CV es completamente autocontenido y funciona sin conexión.
