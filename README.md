# WebSocket Chat Demo

Este proyecto es una demostración simple de un chat en tiempo real usando WebSockets con Node.js, Express y la librería `ws`. Permite a múltiples usuarios conectarse a través de un navegador web y enviar mensajes que se transmiten a todos los clientes conectados.

## Estructura del proyecto

- `src/index.js`: Servidor Node.js que sirve archivos estáticos y gestiona la comunicación WebSocket.
- `public/index.html`: Interfaz web del chat, implementada en HTML y JavaScript.

## Dependencias

- [express](https://www.npmjs.com/package/express)
- [ws](https://www.npmjs.com/package/ws)

## Instalación

1. Clona este repositorio o descarga los archivos.
2. Instala las dependencias ejecutando:

```bash
npm install express ws
```

## Ejecución

1. Inicia el servidor ejecutando con estas alternativas:

```bash
npm run dev
```
```bash
npm start
```
```bash
node .\src\index.js
```

2. Abre tu navegador y accede a [http://localhost:3000](http://localhost:3000)

## ¿Cómo funciona?

- El servidor (`index.js`) sirve la página web y gestiona las conexiones WebSocket.
- Los usuarios ingresan un nombre de usuario y un mensaje en la interfaz web.
- Al enviar un mensaje, este se transmite a todos los clientes conectados en tiempo real.

## Notas

- No se requiere configuración adicional.
- El chat es solo para fines demostrativos y no incluye autenticación ni almacenamiento persistente.
