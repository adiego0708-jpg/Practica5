# P4 — El inventario corrupto

## Requisitos

Node.js 18 o superior. No se necesita `npm install`.

## Cómo ejecutar

```
node server.js
```

Abre **http://localhost:3500**

Para detener: `Ctrl + C`

## Nota importante

No abras `index.html` con doble clic (`file://`) — `fetch()` no va a poder cargar `inventario.json` así. Siempre usa el servidor.

## Estructura

```
server.js
index.html
inventario.xml     <- tiene los errores que debes corregir
css/estilos.css
js/main.js          <- no lo necesitas modificar
```

Tú vas a crear `inventario.json` en esta misma carpeta, a partir de tu `inventario.xml` ya corregido.
