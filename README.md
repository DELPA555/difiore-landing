# Di Fiore Gestión — Landing Page

Sitio estático de una sola página (`index.html` + `assets/`), sin build ni dependencias.

## Estructura
- `index.html` — toda la página (secciones: hero, problema, módulos, capturas, precio, FAQ, cierre)
- `assets/` — logo y capturas del sistema

## Actualizar el link de descarga

El botón "Descargar demo" apunta a la última release publicada en
`DELPA555/difiore-releases`. Cada vez que se publique una versión nueva del instalador, hay
que actualizar la URL en 3 lugares dentro de `index.html` (buscar
`difiore-releases/releases/download/`):
- El botón del nav
- El botón del hero
- El botón del CTA final

## Deploy

Este repo está pensado para conectarse directo a Netlify (Import from Git). Cualquier push a
`main` dispara un deploy automático — no hace falta build command ni carpeta de salida
especial, el sitio ya está listo tal cual en la raíz.
