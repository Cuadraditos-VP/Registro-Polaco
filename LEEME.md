# Registro Polaco

Registro de ventas del puesto: productos con ícono o foto, stock, ticket imprimible y caja del día.
Los datos se guardan en el navegador de cada dispositivo.

## Publicar en GitHub Pages
1. Creá un repositorio nuevo (por ejemplo `registro-polaco`).
2. Subí **todo el contenido** de esta carpeta (index.html, manifest.webmanifest, sw.js y la carpeta icons).
3. Settings → Pages → Branch: `main`, carpeta `/ (root)` → Save.
4. En un par de minutos queda en `https://TU-USUARIO.github.io/registro-polaco/`.

## Instalar en el celular
- **Android (Chrome):** abrí el link → menú ⋮ → *Instalar app* (o *Agregar a pantalla principal*).
- **iPhone (Safari):** abrí el link → botón Compartir → *Agregar a inicio*.

## Al actualizar
Cada vez que reemplaces `index.html`, cambiá en `sw.js` la línea
`const VERSION = "registro-polaco-v1";` por v2, v3… así los celulares toman la versión nueva.
