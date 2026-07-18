# Laboratorio Android 09 — Services y Tareas en Segundo Plano

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white)

Laboratorio Android N.º 9 sobre el manejo de procesos en segundo plano: implementación de Services, tareas diferidas con WorkManager y notificaciones del sistema, incluyendo el manejo de permisos en tiempo de ejecución.

## 📚 Temas cubiertos

- Android Services (Started y Bound)
- WorkManager para tareas diferidas y asíncronas
- Notificaciones del sistema con `NotificationCompat`
- Permisos en tiempo de ejecución (p. ej. `POST_NOTIFICATIONS`)

## 🛠️ Tecnologías

| Tecnología | Uso |
|---|---|
| Kotlin | Lenguaje principal del proyecto |
| Android SDK | Plataforma de desarrollo |
| WorkManager (Jetpack) | Programación de tareas en segundo plano |
| NotificationCompat (AndroidX) | Notificaciones compatibles entre versiones |

## ✅ Requisitos previos

Antes de ejecutar el proyecto asegúrate de tener instalado:

- [Android Studio](https://developer.android.com/studio) (versión reciente, con el Android SDK configurado)
- JDK 17 (incluido en las versiones actuales de Android Studio)
- Un emulador de Android configurado en el AVD Manager **o** un dispositivo físico con la depuración USB activada
- Conexión a internet para la descarga inicial de dependencias de Gradle

## 🚀 Instalación y ejecución

1. Clona el repositorio:

   ```bash
   git clone https://github.com/NinaDIV/Android-Lab09-Services.git
   cd Android-Lab09-Services
   ```

2. Abre Android Studio y selecciona **Open**, apuntando a la carpeta del proyecto (`LAB09/`).
3. Espera a que Gradle sincronice y descargue las dependencias (primera vez puede tardar unos minutos).
4. Selecciona un emulador o dispositivo físico en la barra superior.
5. Ejecuta la app con **Run ▶** (o `Shift + F10`).
6. Al iniciar, la aplicación se instala y abre en el dispositivo; acepta el permiso de notificaciones cuando el sistema lo solicite para probar los ejemplos de Services y notificaciones.

## 📁 Estructura del proyecto

```
Android-Lab09-Services/
├── LAB09/          # Proyecto Android (código fuente Kotlin y configuración de Gradle)
└── README.md
```
