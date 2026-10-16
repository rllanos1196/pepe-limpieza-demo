# PEPE LIMPIEZA — Demo web en Vue 3

Demo comercial responsive construida con Vue 3 + Vite y Lucide Vue Next. Las imágenes de catálogo son vistas de las páginas del PDF entregado, renderizadas como imágenes para conservar su aspecto original.

## Requisitos
- Node.js 20 o superior (recomendado)
- npm

## Ejecutar localmente
```bash
npm install
npm run dev
```
Vite mostrará una dirección local, normalmente `http://localhost:5173`.

## Generar versión de producción
```bash
npm run build
npm run preview
```
La web compilada se genera en `dist/`.

## Personalización antes de publicar
1. Configurar el número de WhatsApp en la función `wa()` de `src/App.vue` (actualmente abre WhatsApp con un mensaje precargado sin número de destino).
2. Confirmar teléfono, correo, dirección, horarios, cobertura de entrega y condiciones comerciales.
3. Reemplazar las tarjetas de páginas por fichas individuales si se desea búsqueda por producto y precios accesibles como texto.
4. Revisar precios y disponibilidad directamente con el negocio. El PDF se ha integrado como vistas de páginas y no se ha inventado un inventario estructurado.

## Estructura
- `src/App.vue`: contenido, navegación, filtros y acciones comerciales.
- `src/style.css`: diseño adaptable para móvil, tablet y escritorio.
- `public/catalogo/`: páginas del catálogo original renderizadas como imágenes.
