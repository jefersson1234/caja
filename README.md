# Caja de sorpresas

Este proyecto es una página web romántica con:

- una carta de mensaje personalizado
- galería de fotos
- caja sorpresa con confetti
- reproductor de música

## Cómo usarlo

1. Ejecuta el proyecto con un servidor local (por ejemplo, la extensión Live Server de VS Code) y abre la URL que genera. Evita abrir `index.html` directamente con `file://`, ya que algunos navegadores bloquean la carga de la música.
2. Edita `config.js` para personalizar:
   - el título
   - el mensaje y firma
   - las rutas de las fotos
   - el título de la canción
3. Si cambias el archivo de música, actualiza `SONG_PATH` en `index.html`.
4. Guarda los archivos de imagen en la carpeta `fotos/`.
5. Guarda el archivo de audio en la carpeta `musica/`.

## Estructura

- `index.html` — diseño y lógica principal
- `config.js` — configuración del contenido
- `fotos/` — imágenes
- `musica/` — audio

## Nota

Usa archivos de audio compatibles con navegador (`.mp3`, `.m4a` o `.ogg`) para que se reproduzcan correctamente.
