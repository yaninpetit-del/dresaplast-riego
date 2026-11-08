# DRESAPLAST · Riego para fincas de León

Web de DRESAPLAST (Zuares del Páramo, León): catálogo de material de riego con fotos de proveedores (VYRSA, RIS Iberia, ITM Filters, Hidroten, Almagromur), calculadora de finca, esquema de instalación, asistente de averías, empresa, servicios y contacto.

## Publicar en GitHub Pages
1. Crea un repositorio nuevo (por ejemplo `dresaplast-riego`).
2. Sube todo el contenido de esta carpeta (index.html, carpeta `img`, carpeta `data`, `.nojekyll`).
3. En el repositorio: **Settings → Pages → Branch: main / root → Save**.
4. En un par de minutos estará en `https://TU-USUARIO.github.io/dresaplast-riego/`.

## Qué funciona en GitHub
- Tienda, catálogo con 209 productos, fotos con segundo ángulo, carrito y pedido por copia.
- Calculadora de finca, esquema de instalación, sondeo animado, contacto (abre el correo).
- El asistente de averías funciona con respuestas guardadas (sin IA).

## Qué NO funciona en GitHub
- El panel de **Gestión** (facturas, precios, averías) y la comparación diaria de precios necesitan la base de datos de la versión en Claude. En GitHub el panel se ve, pero no guarda.
- Para actualizar productos, edita `data/productos.json`.
