# sareyes.com

Base del proyecto estático para **sareyes.com**.

## Estructura

- `index.html` — Página en construcción con meta tags básicos.
- `assets/` — Estáticos (CSS, JS, imágenes, fuentes e íconos).
- `pages/` — Páginas futuras.
- `includes/` — Fragmentos HTML reutilizables.
- `data/` — Configuraciones SEO y del sitio.
- `docs/` — Documentación (guía de estilo, contribución y changelog).
- `scripts/` — Automatizaciones (generar sitemap, optimizar imágenes, etc.).
- `config/` — Configuraciones de despliegue/SEO.

## Uso

1. Sirve estático (por ejemplo con Nginx, GitHub Pages, Netlify o Render).
2. Coloca tu `logo.png` en `assets/images/`.
3. Actualiza `data/seo.json` y `robots.txt` si cambian las rutas.

## SEO

- `robots.txt` y `sitemap.xml` incluidos.
- Meta tags básicos en `index.html` y `/includes/meta-tags.html`.

## Licencia

Privado (ajústalo si quieres publicar).
