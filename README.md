# Estudio Creativo

Sitio web multi‑página de un estudio de diseño creado con **Bootstrap 5** y **SASS**.

## Estructura
- `index.html`
- `servicios.html`
- `nosotros.html`
- `galeria.html`
- `contacto.html`
- `scss/` código fuente SASS
- `css/main.css` hoja de estilos compilada
- `robots.txt` y `sitemap.xml`

## Compilar SASS
1. Instalar [Sass](https://sass-lang.com/install) si no está disponible.
2. Ejecutar:
   ```bash
   npx sass scss/main.scss css/main.css --style=compressed
   ```
   El comando generará `css/main.css` minificado.

## Despliegue
1. Subir todos los archivos del proyecto a un hosting estático (ej. [InfinityFree](https://app.infinityfree.net/) o [000webhost](https://www.000webhost.com/)).
2. Asegurarse de colocar los archivos en la carpeta pública (`htdocs` o `public_html`).
3. Actualizar las URL de `canonical`, `og:url` y `Sitemap` con el dominio final del sitio.

## Licencia
Proyecto para fines educativos.
