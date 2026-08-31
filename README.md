# Línea de tiempo — Gestión de pruebas del proyecto BI Cultural

Sitio estático de una sola página con la trayectoria de la función de pruebas de
software sobre la Bodega de Datos del proyecto BI Cultural (2019–2024).

## Contenido

Versión pública: incluye etapas, funciones, aporte de valor, métricas de pruebas,
tecnologías y hallazgos técnicos. **No incluye nombres de funcionarios ni cifras
presupuestales del proyecto.**

## Publicar en GitHub Pages

`index.html` está en la raíz y no tiene dependencias de build.

1. Sube los archivos a la rama `main`.
2. En el repositorio: **Settings → Pages**.
3. En *Source* elige **Deploy from a branch**, rama `main`, carpeta `/ (root)`.
4. Guarda. El sitio queda en `https://aquilu.github.io/bicult/` en un par de minutos.

## Estructura

- `index.html` — el sitio completo (HTML, CSS y JS en un solo archivo).
- `laminas/` — la lámina panorámica del sistema (JPG para la página, PNG para verla en detalle). **Debe subirse junto al index.**
- Tipografías: Spectral e IBM Plex Sans/Mono desde Google Fonts.
- Sin frameworks, sin dependencias, sin paso de compilación.

## Comportamiento

- **Escritorio (>1080px):** la línea de tiempo es un selector horizontal; se
  navega con clic o con las flechas del teclado.
- **Móvil (≤1080px):** las etapas se despliegan como acordeón.
