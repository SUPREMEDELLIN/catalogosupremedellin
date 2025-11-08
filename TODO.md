# TODO: Organizar rutas de imágenes y actualizar repositorio

## Información recopilada
- Las rutas de imágenes en index.html tienen inconsistencias: algunas con doble "FOTOS CATALOGO/FOTOS CATALOGO/", otras con rutas absolutas "c:\Users\...".
- Estructura de directorios: Hay carpetas anidadas FOTOS CATALOGO/FOTOS CATALOGO/ que contienen subcarpetas como ACCESORIOS, BUSOS L, etc. También hay FOTOS CATALOGO/ con carpetas similares (posible duplicación).
- Necesidad: Aplanar la estructura moviendo contenido de FOTOS CATALOGO/FOTOS CATALOGO/ a FOTOS CATALOGO/, fusionando carpetas si es necesario.

## Plan
1. Mover imágenes de carpetas anidadas FOTOS CATALOGO/FOTOS CATALOGO/ a FOTOS CATALOGO/ usando robocopy para fusionar.
2. Eliminar la carpeta anidada vacía.
3. Actualizar rutas en index.html: cambiar "FOTOS CATALOGO/FOTOS CATALOGO/" a "FOTOS CATALOGO/", y rutas absolutas a relativas.
4. Verificar que las imágenes se carguen correctamente.

## Pasos a completar
- [x] Mover contenido de FOTOS CATALOGO/FOTOS CATALOGO/ a FOTOS CATALOGO/
- [x] Eliminar carpeta anidada
- [x] Actualizar rutas en index.html
- [x] Verificar imágenes
