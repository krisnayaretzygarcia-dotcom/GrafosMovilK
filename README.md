# Grafos Móvil

Aplicación Android nativa desarrollada en Kotlin para practicar grafos no dirigidos.

## Funciones
- Visualización de vértices y aristas.
- Agregar vértices (máximo 12).
- Agregar aristas sin dirección y sin duplicados.
- Recorridos BFS y DFS desde un vértice elegido.
- Consulta de la matriz de adyacencia.
- Reinicio del grafo.

## Requisitos
- Android Studio Ladybug o posterior.
- JDK 17.
- Android SDK Platform 35.
- Android 6.0 (API 23) o posterior para ejecutar la app.

## Abrir y compilar
1. Descomprime `GrafosMovil.zip`.
2. Abre Android Studio y selecciona **Open**.
3. Selecciona la carpeta `GrafosMovil` (la que contiene `settings.gradle.kts`).
4. Espera a que termine Gradle Sync.
5. Para probar: conecta el teléfono con depuración USB o inicia un emulador y pulsa **Run**.
6. Para generar el APK: **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
7. El APK de depuración se genera en `app/build/outputs/apk/debug/app-debug.apk`.

La carpeta `app/build` se crea al compilar. No se incluye un APK precompilado porque este entorno no dispone de Android SDK/Gradle para compilarlo aquí.
