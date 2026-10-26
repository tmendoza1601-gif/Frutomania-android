# FRUTOMANÍA — prototipo Android 3D

Prototipo de mundo abierto en Godot 4: cámara en tercera persona, personajes Fresa/Piña/Guayaba, monedas y misiones, joystick táctil, salto, interacción y cambio de personaje. Esta edición añade una casa con interior visitable, muebles básicos, dos Fruta-móviles conducibles y controles táctiles para conducir.

## Si solo tienes un teléfono Android

Consulta `GUIA_DESDE_EL_TELEFONO.md`. Incluye una ruta para solicitar una compilación APK gratis mediante GitHub Actions desde el navegador del teléfono. Se añadió un preset de exportación Android y un workflow, pero aún no se ha confirmado una compilación real.

## Abrir y probar en Godot

1. Descarga Godot 4 desde https://godotengine.org/download/.
2. Abre el proyecto `project.godot`.
3. Ejecuta el proyecto. Teclado en escritorio: WASD o flechas para moverte, espacio para saltar, E para interactuar, Q para cambiar de fruta.

## Exportar a Android

Se incluye `export_presets.cfg` con un preset Android de prueba. La exportación local de Godot requiere las plantillas de exportación y Android SDK/JDK configurados. La guía para hacerlo desde teléfono usa compilación en la nube.

## Todo gratis

Godot y las herramientas Android son gratuitas. El código y las formas geométricas de este prototipo no requieren comprar recursos. GitHub Actions ofrece límites gratuitos sujetos a sus condiciones. Publicar en Google Play puede requerir una tarifa de registro; instalar el APK para probarlo en tu teléfono no requiere publicar en Play Store.

## Controles

- Escritorio: WASD/flechas para moverte, espacio para saltar, E para interactuar, Q para cambiar de fruta.
- Android: joystick izquierdo; botón de salto; acción para hablar, recoger, entrar/salir de casa o entrar/salir del coche; cambiar para alternar personaje. Cerca de un coche, acción lo conduce. En coche, joystick arriba/abajo acelera/frena y izquierda/derecha gira.
