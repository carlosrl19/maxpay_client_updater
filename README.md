# maxpay_client_updater ⚡

## 📌 Pasos para publicar un nuevo update

- Actualizar el archivo version.json del repositorio actual con la nueva versión del apk
- Subir el APK al release (nombre `maxpay-versión.apk`)
- Actualizar la versión en pubspec.yaml de Flutter con la nueva versión del apk

Repo publico de pruebas para subir el apk actualizado de maxpay.

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

## 🚀 Rápido inicio

1. Clona el repositorio:

```bash
git clone https://github.com/Soluciones-de-integracion-empresarial/maxpay_client
cd maxpay_client
```

2. Instala dependencias:

```bash
flutter pub get
```

3. Ejecuta en modo desarrollo (emulador o dispositivo conectado):

```bash
flutter run
```

Compilar para producción (Android):

```bash
flutter build apk --release
```

Compilar para iOS (requiere macOS/Xcode):

```bash
flutter build ios --release
```

---

## 🧭 Scripts y comandos útiles
- `flutter run` — Ejecutar en dispositivo/emulador
- `flutter build apk` — Generar APK de Android
- `flutter build ios` — Generar build de iOS
- `flutter test` — Ejecutar tests

---

## 🗂 Estructura relevante
- `lib/main.dart` — Entrada de la app
- `lib/services/` — Lógica para llamadas a APIs (ver `api_service.dart`)
- `lib/models/` — Modelos de datos (transacciones, terminales, usuarios...)
- `lib/screens/` — Pantallas y rutas de la UI
- `lib/widgets/` — Componentes reutilizables

---

## 🔌 Conexión con el backend
- El servicio principal de HTTP está en `lib/services/api_service.dart`.
---

## 🧪 Tests
- `flutter test` — ejecuta pruebas unitarias y de widgets.

---

## 📬 Contacto
- Para integraciones, dudas o problemas, abre un issue en este repositorio o contacta al equipo responsable.
