# Sitio Operativo Brisa Salud
Sitio estático (HTML/CSS/JS) con despliegue en Netlify.

## Estructura
- `/assets/css/core.css` estilos base
- `/assets/js/core.js` bootstrap mínimo
- `netlify.toml` headers de seguridad, caché y CSP

##CI
GitHub Actions (Site CI) levanta server local y corre Lighthouse (perf, a11y, bp, seo). Artefacto: `lhr.json`.

## KPIs
- Lighthouse ≥ 95 en las 4 categorías
- Headers de seguridad activos
- Caché immutable en `/assets/*`
