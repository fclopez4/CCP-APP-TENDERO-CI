# CCP-APP-TENDERO

CCP-APP-TENDERO es una aplicación móvil desarrollada con Ionic y Angular. Esta aplicación está diseñada para proporcionar una experiencia de usuario fluida y moderna, utilizando las últimas tecnologías web y móviles.

## Características

- **Internacionalización**: Soporte para múltiples idiomas utilizando `@ngx-translate/core`.
- **Temas y estilos**: Personalización de estilos con SCSS y Tailwind CSS.
- **Integración con Capacitor**: Soporte para funcionalidades nativas en Android.
- **Componentes reutilizables**: Uso de componentes modulares y reutilizables.

## Estructura del Proyecto

El proyecto tiene la siguiente estructura de directorios:

```
.
├── android/
├── resources/
├── src/
│   ├── app/
│   ├── assets/
│   ├── environments/
│   ├── scss/
│   ├── theme/
│   ├── index.html
│   ├── main.ts
│   ├── polyfills.ts
│   └── test.ts
├── .browserslistrc
├── .editorconfig
├── .eslintrc.json
├── .gitignore
├── angular.json
├── capacitor.config.ts
├── ionic.config.json
├── karma.conf.js
├── package.json
├── tsconfig.app.json
├── tsconfig.json
└── tsconfig.spec.json
```

## Instalación

Para instalar y configurar el proyecto, sigue estos pasos:

1. Clona el repositorio:
    ```sh
    git clone <URL_DEL_REPOSITORIO>
    cd CCP-APP-TENDERO
    ```

2. Instala las dependencias:
    ```sh
    npm install
    ```

3. Genera los recursos de la aplicación:
    ```sh
    npm run resources
    ```

## Ejecución

Para ejecutar la aplicación en un entorno de desarrollo, utiliza el siguiente comando:

```sh
npm start
```

Para construir la aplicación para producción:

```sh
npm run build
```

## Despliegue en Android

Para desplegar la aplicación en un dispositivo Android, sigue estos pasos:

1. Construye la aplicación y copia los archivos a la plataforma Android:
    ```sh
    npm run android
    ```

2. Para ejecutar la aplicación en modo de desarrollo en un dispositivo Android:
    ```sh
    npm run android-live
    ```

3. Para sincronizar los cambios con la plataforma Android:
    ```sh
    npm run android-sync
    ```

## Pruebas

Para ejecutar las pruebas unitarias, utiliza el siguiente comando:

```sh
npm test
```

## Linting

Para verificar el código con ESLint, utiliza el siguiente comando:

```sh
npm run lint
```

Para generar el apk ejecuta el comando
```sh
cd android
./gradlew assembleDebug
```

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o envía un pull request para cualquier mejora o corrección.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

## Contacto

Para más información, puedes contactar al autor del proyecto en [correo@example.com](mailto:correo@example.com).
