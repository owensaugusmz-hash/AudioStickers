# AudioStickers Android

Proyecto Android sencillo que empaqueta la aplicación web AudioStickers dentro de una app Android usando WebView.

## Compilar APK
1. Sube **todo el contenido de este ZIP** a la raíz de tu repositorio GitHub `AudioStickers`.
2. Asegúrate de que también se suba la carpeta oculta `.github`.
3. Abre la pestaña **Actions**. El flujo `Compilar APK` se ejecutará automáticamente.
4. Cuando termine en verde, abre la ejecución y descarga el artefacto `AudioStickers-debug-apk`.
5. Dentro encontrarás `app-debug.apk`, que puedes instalar en tu Android.

## Nota
La app permite crear una imagen tipo sticker y asociarle un audio para compartir ambos archivos. WhatsApp no reproduce audio al tocar un sticker normal; por eso se comparten la imagen y el audio como archivos separados.
