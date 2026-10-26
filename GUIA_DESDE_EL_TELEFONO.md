# FRUTOMANÍA: generar el APK usando solo tu teléfono

Esta ruta usa herramientas gratuitas. No hace falta una computadora, pero sí conexión a internet para que GitHub compile el proyecto en la nube.

## Opción A: compilar gratis en la nube desde el navegador del teléfono

1. Descarga y descomprime el ZIP del proyecto en tu teléfono si puedes. Si no tienes una app para descomprimir ZIP, instala una gratuita de confianza desde Google Play.
2. En el navegador del teléfono, crea una cuenta gratuita en https://github.com/ si todavía no tienes una.
3. Crea un repositorio nuevo. Para facilitar el proceso, marca el repositorio como **Public** y no añadas README, licencia ni archivos iniciales.
4. Sube el contenido de la carpeta `FrutomaniaAndroid` al repositorio, incluyendo `project.godot`, `main.tscn`, `scripts`, `export_presets.cfg` y `.github/workflows/build-android.yml`. GitHub móvil puede ser más cómodo con la opción de subir archivos desde el navegador en modo escritorio.
5. Abre la pestaña **Actions** del repositorio y habilita los workflows si GitHub lo pide.
6. Selecciona **Build FRUTOMANIA Android APK** y pulsa **Run workflow**. También se ejecuta cuando subes cambios a la carpeta del proyecto.
7. Espera a que el trabajo termine en verde. Abre esa ejecución y busca **Artifacts**; descarga `FRUTOMANIA-Android-APK`.
8. Descomprime el artefacto ZIP y toca `Frutomania.apk`. Android podría pedirte permiso para instalar apps desde el navegador o gestor de archivos; actívalo solo para la app que usas para instalar y luego puedes desactivarlo.

## Importante

- El servicio gratuito de GitHub Actions tiene límites y condiciones de uso; un repositorio público suele ser la ruta más sencilla para mantener el coste en cero.
- Este flujo es una configuración inicial y no se ha verificado mediante una compilación real en esta sesión. Si la compilación falla, abre el registro del trabajo y comparte el mensaje de error para corregirlo.
- El APK exportado con la clave de depuración sirve para pruebas personales. No es un APK de publicación firmado con una clave de lanzamiento propia.
- Nunca publiques claves, contraseñas ni datos privados en el repositorio.
