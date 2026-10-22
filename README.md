# El universo en 24 horas

Experiencia de lectura en español. Sitio estático, sin instalación ni compilación.

## Vista previa

Desde esta carpeta: `python -m http.server 8765 --bind 127.0.0.1 --directory dist`.
Abrir http://127.0.0.1:8765.

## Archivos

- `dist/index.html`: contenido, fechas, explicación y fuentes.
- `dist/styles.css`: dirección visual original.
- `dist/finish.css`: ajustes finales de lectura, accesibilidad y móvil.
- `dist/script.js`: estrellas, pausa, reloj de hitos y progreso de lectura.
- `.openai/hosting.json`: identidad del sitio y carpeta de publicación. Conservar su project_id.
- `docs/REVISION.md`: revisión, decisiones y límites de verificación.

Para otro alojamiento estático, publicar solamente el contenido de dist.
Google Fonts necesita conexión; hay tipografías de respaldo.
