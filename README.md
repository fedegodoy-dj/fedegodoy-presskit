# Fede Godoy · Presskit

Landing de presskit de Fede Godoy (DJ, Córdoba, Argentina). Sitio estático: un `index.html`, la carpeta `img/` y nada para compilar.

## Publicar en Vercel

1. Subí esta carpeta a un repositorio de GitHub.
2. En vercel.com: **Add New → Project**, elegí el repositorio.
3. Framework Preset: **Other**. Sin Build Command ni Output Directory (dejalos vacíos).
4. **Deploy**. Cada `git push` vuelve a publicar solo.

## Después del primer deploy

- Cuando tengas el dominio final (por ejemplo `fedegodoy.vercel.app` o uno propio), cambiá en `index.html` la línea
  `<meta property="og:image" content="/img/og.jpg">` por la URL completa, por ejemplo
  `https://fedegodoy.vercel.app/img/og.jpg`. Así WhatsApp e Instagram muestran la vista previa con foto.

## Editar contenido

- Textos, links y email: todo está en `index.html`.
- Fotos: reemplazá el archivo en `img/` manteniendo el mismo nombre, o cambiá el `src` en `index.html`.
- Las animaciones son CSS + un poco de JavaScript propio, sin librerías externas: scroll por pantalla (scroll-snap), entrada animada de cada página y carrusel automático de fotos. Con "reducir movimiento" activado en el sistema, la página se muestra sin animaciones.

Fotos: [@cente.capturas](https://www.instagram.com/cente.capturas/)
