# Leñadores de Asís · Bodas de Plata 2026

Galería conmemorativa de la Promoción 2001 «Arges Dei» del Colegio San Francisco de Asís.
Página estática para GitHub Pages con código QR.

## Archivos
- `index.html` — la galería que ven los visitantes (no se edita).
- `fotos.json` — la lista de fotos y sus textos (esto es lo que se actualiza).
- `fotos/` — carpeta donde viven las imágenes.
- `generador.html` — herramienta privada para crear el `fotos.json` sin escribir código.

## Cómo añadir o cambiar fotos
1. Sube tus imágenes a la carpeta `fotos/` en GitHub.
2. Abre `generador.html`, añade esas mismas fotos, escribe el texto de cada una y ordénalas.
3. Descarga el `fotos.json` que genera y súbelo al repositorio (reemplaza el que existe).

Formato de `fotos.json`:
```json
[
  { "archivo": "nombre-de-la-foto.jpg", "texto": "Una línea de texto" }
]
```

> Las fotos de ejemplo (`ejemplo-1.jpg` … `ejemplo-4.jpg`) son solo de muestra. Puedes borrarlas cuando subas las reales.
