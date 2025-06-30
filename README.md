# PNYX

PNYX es una red social móvil desarrollada en Flutter, centrada en el debate y la participación ciudadana. Permite a los usuarios publicar, comentar, guardar publicaciones y seguir a otros usuarios, todo en un entorno seguro y moderno.

## Características

- Registro e inicio de sesión de usuarios
- Publicación y visualización de posts y comentarios
- Guardado de publicaciones favoritas
- Seguimiento y gestión de usuarios
- Filtros por temas y país
- Interfaz moderna y adaptable (Material 3)
- Soporte multiplataforma: Android, iOS, Web, Windows, Linux, macOS

## Estructura del proyecto

- `lib/`: Código fuente principal de la app
  - `screens/`: Pantallas principales (login, registro, perfil, posts, etc.)
  - `services/`: Servicios de red, autenticación y almacenamiento local
  - `models/`: Modelos de datos (usuario, post, etc.)
  - `data/`: Constantes, rutas y temas de la app
  - `widgets/`: Componentes reutilizables
- `assets/`: Recursos gráficos (imágenes, iconos, fuentes)
- `android/`, `ios/`, `web/`, `windows/`, `linux/`, `macos/`: Plataformas soportadas

## Instalación y ejecución

1. Clona este repositorio:
   ```sh
   git clone https://github.com/tuusuario/pnyx.git
   cd pnyx
   ```
2. Instala las dependencias:
   ```sh
   flutter pub get
   ```
3. Ejecuta la app:
   ```sh
   flutter run
   ```

## Configuración

- El backend está configurado en [`AppData.backendUrl`](lib/data/app_data.dart).
- Para cambiar el nombre, correo o datos de la empresa, edita [`AppData`](lib/data/app_data.dart).

## Contribución

¡Las contribuciones son bienvenidas! Abre un issue o pull request para sugerir mejoras o reportar errores.

## Licencia

Este proyecto está bajo la licencia MIT.

---

Desarrollado por Miguel Ceada y Carlos Sánchez