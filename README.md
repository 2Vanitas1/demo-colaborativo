# Nombre del proyecto

Descripción breve de qué hace esta aplicación Node.js y para quién está pensada.

## Requisitos

- [Node.js](https://nodejs.org/) 18 o superior
- npm (incluido con Node.js) o [pnpm](https://pnpm.io/) / [yarn](https://yarnpkg.com/)

## Instalación

```bash
git clone <url-del-repositorio>
cd nombre-del-proyecto
npm install
```

Copia las variables de entorno de ejemplo y ajústalas:

```bash
cp .env.example .env
```

## Uso

Arranca el servidor de desarrollo:

```bash
npm run dev
```

Compila o inicia en producción:

```bash
npm start
```

Por defecto la aplicación queda disponible en `http://localhost:3000`.

## Scripts

| Script          | Descripción                          |
| --------------- | ------------------------------------ |
| `npm run dev`   | Arranca en modo desarrollo           |
| `npm start`     | Arranca en modo producción           |
| `npm test`      | Ejecuta las pruebas                  |
| `npm run lint`  | Revisa el estilo y errores del código |

## Estructura del proyecto

```text
.
├── src/              # Código fuente
├── tests/            # Pruebas
├── package.json
└── README.md
```

## Variables de entorno

| Variable     | Descripción              | Ejemplo        |
| ------------ | ------------------------ | -------------- |
| `PORT`       | Puerto del servidor      | `3000`         |
| `NODE_ENV`   | Entorno de ejecución     | `development`  |

## Contribución

1. Crea una rama a partir de `main`.
2. Haz tus cambios y añade pruebas si aplica.
3. Abre un pull request describiendo el cambio.

## Licencia

Este proyecto se distribuye bajo la licencia MIT. Ver `LICENSE` para más detalles.
