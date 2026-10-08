# genero.mapeo.social — Mapa de género

Explorador estático (un solo `index.html`, sin build) de 163 organizaciones con agendas de género en el Perú.
Se publica con GitHub Pages en `genero.mapeo.social`. Ver `PUBLICAR.md` (en la carpeta de entrega) para el paso a paso.

## Antes de publicar
1. En `index.html` busca `CAMBIAR@chakakuna.com` y pon el correo real que recibirá sumas, correcciones y retiros (los formularios abren el correo de quien participa; no guardan nada en un servidor).
2. Confirma que quieren publicar los datos de contacto de las organizaciones (consentimiento / flujo de retiro).

## Contenido
- `index.html` — página, estilos, datos (array `DATA`) y lógica.
- `CNAME` — `genero.mapeo.social` (no borrar).
- `robots.txt`, `sitemap.xml`, `llms.txt` — indexación para buscadores e IA.
- `fonts/` — Bricolage Grotesque y DM Sans (SIL OFL), alojadas aquí.
- `img/og-image.png` — imagen al compartir en redes (puede reemplazarse por una captura del mapa).
- `404.html`, favicon e iconos, `.nojekyll`.

## Actualizar los datos
Los datos viven dentro de `index.html` en la constante `DATA`. Al actualizar el mapeo, cambia `Datos al 2024` (2 lugares), la fecha en `sitemap.xml` y el conteo (163) en `<title>`/meta/`llms.txt`.
