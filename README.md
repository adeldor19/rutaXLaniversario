# Rutas 360 · Guía turística inmersiva

Prototipo web para recorridos culturales y educativos con fotografías panorámicas 360°, puntos interactivos y audioguía.

## Publicación en GitHub Pages

1. Entra en **Settings → Pages**.
2. En **Build and deployment**, selecciona **Deploy from a branch**.
3. Elige la rama `main` y la carpeta `/(root)` y guarda.
4. Cuando GitHub termine la publicación, la web estará disponible en:
   https://adeldor19.github.io/rutaXLaniversario/

## Cómo incorporar panorámicas propias

1. Exporta cada foto desde Insta360 como panorámica JPG equirectangular (idealmente proporción 2:1).
2. Crea la carpeta `assets/panoramas/` y sube allí las imágenes optimizadas.
3. En `index.html`, sustituye las imágenes de demostración en la sección `<a-assets>` por rutas locales, por ejemplo `assets/panoramas/plaza.jpg`.
4. Actualiza la lista `stops` con el nombre, descripción, texto de audioguía y archivo de cada parada.

## Notas

- La entrada en realidad virtual depende del navegador y del modelo concreto de gafas. Se necesita HTTPS para las capacidades WebXR.
- Las panorámicas actuales son demostraciones genéricas, no ubicaciones reales de una ruta.
- Para publicar fotografías de personas, conviene revisar permisos y privacidad.
