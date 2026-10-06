TRUE GLASS AUTO - PWA

Archivos para publicar en GitHub Pages:
- index.html
- manifest.webmanifest
- service-worker.js
- icons/
- assets/true-glass-auto.png

Publicar todos los archivos conservando esta estructura. La PWA requiere HTTPS o localhost para que el service worker funcione.
En iPhone: abrir la URL publicada en Safari > Compartir > Anadir a pantalla de inicio.

ACTUALIZACION DEL LOGO - 6 de octubre de 2026
El PNG oficial se conserva sin modificaciones (1774 x 887, RGBA con transparencia
real) en assets/true-glass-auto.png. Se usa en el panel, el encabezado de la factura
y la marca de agua. No eliminar la carpeta assets.

Iconos: apple-touch-icon.png (180 x 180), icon-192.png (192 x 192) e
icon-512.png (512 x 512). Conservan el logo completo y sus proporciones sobre
una base azul clara #DFF2FF, adecuada para el icono de inicio de iOS.
El manifest declara los iconos como any; no se fuerza un recorte maskable.

Para publicar: descomprimir y subir TODO el contenido a la raiz del repositorio.
index.html debe quedar directamente en la raiz, sin una carpeta contenedora.
Activar GitHub Pages para la rama correspondiente y la carpeta / (root).
La cache se actualizo a true-glass-auto-v2-official-logo.

Verificacion: logo original identico, canal alfa, proporciones, vista de escritorio,
vista movil simulada, estilos de impresion, calculos, ambos modos de impuesto,
agregar/eliminar vehiculos e items, limpiar factura y carga offline del logo.
El JavaScript de facturacion se conserva exactamente como en el paquete original.
Las pruebas se realizaron en Edge/Chromium; no se probaron en un iPhone fisico.
Se mantiene la dependencia original de Tailwind CDN: la primera carga requiere Internet.
