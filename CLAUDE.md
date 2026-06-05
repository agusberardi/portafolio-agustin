# Portfolio Personal — Agustín Berardi

Sitio de portafolio personal estático en HTML y CSS puro. Sin frameworks, sin librerías externas, sin Google Fonts.

## Archivos

- `index.html` — toda la estructura del sitio
- `styles.css` — único archivo de estilos

## Secciones

1. **Nav** — fija, se vuelve semiopaca con blur al hacer scroll (3 líneas de JS inline)
2. **Hero** — nombre, rol y CTA; animación fade-up con `@keyframes`
3. **Sobre mí** — texto descriptivo + chips de habilidades
4. **Proyectos** — grid de tarjetas con hover; tarjeta 1 es "Control de Horas" (real), tarjetas 2 y 3 son placeholder
5. **Contacto** — links a GitHub (`https://github.com/agusberardi`) y email
6. **Footer** — línea de crédito

## CSS

- Variables en `:root`: `--color-bg`, `--color-surface`, `--color-border`, `--color-text`, `--color-muted`, `--color-accent`
- Paleta dark: fondo `#0f0f0f`, superficie `#1a1a1a`, acento `#4f8ef7`
- Tipografía: stack de sistema (`'Segoe UI', system-ui, sans-serif`)
- Responsive con breakpoints en `768px` y `480px`
- Grid de proyectos: `repeat(auto-fill, minmax(300px, 1fr))`

## Restricciones

- Sin frameworks CSS (no Bootstrap, no Tailwind)
- Sin librerías JS
- Sin fuentes externas (no Google Fonts, no CDN de iconos)
- Iconos como SVG inline
- Compatible con apertura directa por `file://` (sin servidor)
