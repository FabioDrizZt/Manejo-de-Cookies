# Node.js Cookie Management Example 🍪

Este repositorio contiene un ejemplo básico de manejo de cookies en una aplicación Node.js utilizando Express y cookie-parser.

## Funcionalidades ✨

- **Establecer una Cookie:** Al acceder a la ruta principal (`/`), se establece una cookie con la fecha y hora actuales.
- **Leer la Cookie:** La ruta `/leer-cookie` muestra la fecha y hora del último acceso almacenado en la cookie.
- **Eliminar la Cookie:** La ruta `/eliminar-cookie` elimina la cookie almacenada, si existe.

## Requisitos 📋

- Node.js instalado en tu sistema.
- Dependencias instaladas: `express` y `cookie-parser`.

## Configuración ⚙️

1. Clona este repositorio en tu máquina local.
2. Instala las dependencias usando `npm install`.
3. Crea un archivo `.env` en la raíz del proyecto y define la variable `PORT`.

## Ejecución ▶️

Para ejecutar la aplicación, utiliza el siguiente comando:

```bash
npm start
```

Esto iniciará el servidor en el puerto especificado en tu archivo .env.

## Endpoints 🛣️
- Principal: GET / - Establece una cookie con la fecha y hora actuales.
- Leer Cookie: GET /leer-cookie - Muestra la fecha y hora del último acceso almacenado en la cookie.
- Eliminar Cookie: GET /eliminar-cookie - Elimina la cookie almacenada, si existe.

## Contribuciones 🤝
Siéntete libre de realizar sugerencias o mejoras mediante pull requests.

## Licencia 📄
Este proyecto está bajo la Licencia MIT - consulta el archivo LICENSE para más detalles.
