# Laparoscopia IMC — Propuesta de rediseño

Mockup de rediseño visual para https://www.laparoscopiaimc.com.ar/, hecho a partir
del sitio actual (WordPress + WooCommerce, theme Flipmart).

## Contenido

- `index.html` — propuesta final, autocontenida (imágenes embebidas en base64).
  Incluye un toggle "Escritorio / Mobile" arriba de todo para previsualizar
  ambas versiones sin salir del archivo.
- `template.html` — misma página con placeholders `__IMG_*__` en lugar de las
  imágenes embebidas, para poder regenerar `index.html` con otras fotos.
- `assets/` — fotos de producto originales usadas en el mockup (bajadas del
  sitio actual).

## Motivación del rediseño

- El sitio actual trata el catálogo como e-commerce (carrito, wishlist) cuando
  el negocio es venta consultiva de equipo capital a hospitales/clínicas.
- El plugin de precios está roto (no se muestra ningún precio).
- Paleta y tipografía genéricas de plantilla, sin relación con el producto.

La propuesta usa una identidad tipo "placa de instrumento" (inspirada en las
placas grabadas de los propios equipos IMC), reemplaza carrito/wishlist por un
CTA de "Consultar precio" por WhatsApp en cada producto, y sube el trust bar
de hospitales/clientes que hoy está escondido en el footer.

Esto es solo una propuesta visual — no está conectado al WordPress real.
