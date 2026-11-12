# MI JUEGO — proyecto Android

Este proyecto empaqueta el prototipo jugable HTML en una aplicación Android offline (WebView local).

## Crear la APK desde un teléfono
1. Crea un repositorio nuevo en GitHub.
2. Descomprime este ZIP y sube el contenido de la carpeta `MI_JUEGO_Android` al repositorio (debe quedar `.github`, `app`, `build.gradle`, etc. en la raíz).
3. Abre la pestaña **Actions** y ejecuta **Crear APK de MI JUEGO** (o espera a que termine el flujo automático).
4. Abre la ejecución terminada, baja **MI-JUEGO-APK** y extrae `app-debug.apk`.
5. Abre el APK en tu Android y permite instalar aplicaciones desde esa fuente si el teléfono lo solicita.

## Estado y límites
- Funciona sin Internet porque el juego se carga desde `assets/index.html`.
- Está configurado para Android 6.0 o superior y orientación horizontal.
- Esta APK contiene el prototipo 2D con perspectiva y controles táctiles, no un juego 3D completo tipo PES/FIFA. Los equipos actuales son genéricos (verdes y rojos); los escudos, plantillas y gráficos 3D reales requieren desarrollo adicional.
