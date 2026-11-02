# Lumbra Iluminación — Prototipo

Prototipo navegable de un catálogo de productos (solo front) para mostrar al cliente.

## Qué incluye

- Portada con categorías y productos destacados.
- Buscador global con sugerencias mientras se escribe.
- Catálogo con filtros por categoría, uso (interior/exterior) y tono de luz, y orden por precio.
- Ficha de producto con galería, especificaciones, botón de consulta por WhatsApp y bloque de video.
- Demo del panel CMS (`#admin`): editar, crear y eliminar productos, subir fotos y pegar links de YouTube.

## Importante

- Los productos, precios e imágenes son **datos de ejemplo**.
- Los cambios hechos en el panel CMS de la demo **se borran al recargar** la página.
- El sitio tiene `noindex` para que no aparezca en Google mientras sea un prototipo.

## Estructura

```
index.html    Toda la página (HTML, CSS y JS en un solo archivo)
vercel.json   Cabeceras de seguridad para el despliegue en Vercel
```

## Despliegue en Vercel

1. En vercel.com → **Add New… → Project**.
2. Importar este repositorio desde GitHub.
3. Framework Preset: **Other**. Sin comando de build. Output directory: la raíz.
4. **Deploy**.

Cada push a `main` vuelve a publicar el sitio automáticamente.

## Próximos pasos (sitio real)

- Pasar a Astro con los productos en archivos de contenido.
- Sumar un CMS headless (Decap CMS o Sanity) para que el cliente edite productos.
- Embeber los videos de YouTube en la ficha de producto.
- Publicar en la cuenta del cliente con su dominio propio.
