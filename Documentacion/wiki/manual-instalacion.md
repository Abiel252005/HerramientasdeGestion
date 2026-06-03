# Manual breve de instalación del proyecto

## Requisitos previos

- Node.js 20 o superior.
- npm 10 o superior.
- Git instalado.
- Visual Studio Code u otro editor.
- Conexión a internet para descargar dependencias.

## Instalación local

1. Clonar o descomprimir el repositorio.

```bash
git clone <URL_DEL_REPOSITORIO>
cd huerto-Connect-develop
```

2. Instalar dependencias.

```bash
npm install
```

3. Ejecutar el servidor de desarrollo.

```bash
npm start
```

4. Abrir la aplicación en el navegador.

```text
http://localhost:4200/
```

## Compilación para producción

```bash
npm run build
```

Los archivos compilados se generan en la carpeta `dist/`.

## Variables y configuración

La URL de la API se define en:

```text
src/environments/environment.ts
```

Ejemplo actual:

```ts
export const environment = {
  production: false,
  apiUrl: 'http://localhost:8000',
};
```

## Notas importantes

- Este ZIP contiene el frontend Angular.
- La API de autenticación o servicios backend debe ejecutarse por separado si se requiere probar el flujo completo de login, OTP, usuarios y sesiones.
- Para pruebas visuales de la landing page y componentes mock del panel, basta con ejecutar `npm start`.
