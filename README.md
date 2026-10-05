# Mis marcas

PWA personal, local y sin cuenta para registrar marcas de ejercicios.

## Desarrollo

Es una aplicación estática. Abrí `dist/index.html` con un servidor local para contar con Service Worker e IndexedDB.

## Datos

Las marcas se guardan únicamente en el navegador mediante IndexedDB. El despliegue y las actualizaciones no las borran. Usá **Ajustes → Exportar datos** como respaldo.

## Publicación

Cada push a `main` publica automáticamente el contenido de `dist` en GitHub Pages mediante `.github/workflows/deploy-pages.yml`.
