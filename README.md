Abstract-Entity-image-uploader
==============================


Uso:

1-Extiende cualquier entity y se añadirá un campo de imagen.
2-Implemente la  getUploadDir(); para que devuelve la ruta y directorio donde se van a subir las imágenes
3-En el FormType añade un campo file tipo file. Validación normal.

Ojo:
Cuando despliegas la aplicación quizás sea necesario cambiar la ruta en la getUploadRootDir() según la estructura de tus carpetas
