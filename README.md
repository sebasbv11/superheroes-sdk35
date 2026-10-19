# Superhéroes — codelab con SDK 35

Proyecto completo basado en la solución oficial de Android Developers:
https://developer.android.com/codelabs/basic-android-kotlin-compose-practice-superheroes?hl=es-419
https://github.com/google-developer-training/basic-android-kotlin-compose-training-superheroes

## Configuración
- compileSdk: 35 (Android 15).
- targetSdk: 35.
- minSdk: 24, como pide el codelab.
- Kotlin 2.1.0, Compose BOM 2024.11.00, Material 3.
- Android Gradle Plugin 8.8.0 y Gradle 8.12.
- Usar JDK 21 para Gradle. El JDK 25 incluido en este Android Studio no es compatible con esta configuración.

## Contenido
- Clase Hero y repositorio con seis héroes.
- LazyColumn con tarjetas, imágenes de 72 dp y animación de entrada.
- Barra superior centrada, fuentes Cabin y formas del codelab.
- Temas claro y oscuro; colores dinámicos desactivados.
- Edge-to-edge e insets de Scaffold, con iconos de las barras del sistema según el tema.
- Traducción al español en res/values-es; recursos originales en inglés como respaldo.

## Abrir y compilar
1. En Android Studio, elegir File > Open y seleccionar esta carpeta.
2. Seleccionar JDK 21 en Settings > Build, Execution, Deployment > Build Tools > Gradle.
3. Sincronizar Gradle y ejecutar la configuración app.

Configura el SDK de Android en Android Studio y selecciona JDK 21 para Gradle. Las rutas locales del SDK y del JDK no se publican en el repositorio.

Desde PowerShell, con JAVA_HOME apuntando al JDK 21:
```powershell
.\gradlew.bat assembleDebug lintDebug
```

Se conservan LICENSE y ASSETS_LICENSE.txt del proyecto oficial.
