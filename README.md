# maxpay_client_updater ⚡

## 📌 Pasos para publicar un nuevo update

- Actualizar el archivo version.json del repositorio maxpay_client_updater con la nueva versión del apk
- Subir el APK al release (nombre `maxpay-v1.0.5.apk`)
- Actualizar la versión en pubspec.yaml de Flutter con la nueva versión del apk (`version: 1.0.5+5`)
> [!NOTE]
> Es obligatorio agregar todo el esquema de versionado en el pubspec.yaml `X.Y.Z+B` explicado a continuación:

## 🧩 Esquema de versionado (Semantic Versioning)

El proyecto sigue el formato `X.Y.Z+B`

Ejemplo: `version: 1.0.2+2`

Significado de cada parte:
- X (Major)
Cambios grandes o incompatibles con versiones anteriores.
- Y (Minor)
Nuevas funcionalidades que mantienen compatibilidad.
- Z (Patch)
Corrección de errores y pequeños ajustes.
- B (Build)
Número de compilación interna.

[![Flutter](https://img.shields.io/badge/Flutter-<latest>-02569B?logo=flutter)](https://flutter.dev/) [![Dart](https://img.shields.io/badge/Dart->=2.19-blue?logo=dart)](https://dart.dev/)

> App cliente móvil de Maxpay para terminales POS y gestión de transacciones.

✨ ¿Qué es?
- Aplicación Flutter que actúa como cliente para las APIs de Maxpay: procesa pagos, muestra historiales, maneja canjes y cierres de turnos desde terminales.
- Comunicación con el backend a través de servicios en `lib/services` y modelos en `lib/models`.

🎨 Tecnologías
- **Flutter**
- **Dart**
- Arquitectura con servicios en `lib/services` y pantallas en `lib/screens`

---
