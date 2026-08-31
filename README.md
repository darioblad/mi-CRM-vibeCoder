# Mi CRM vibeCoder

Landing page de **Nexo CRM**: gestión de clientes, e-commerce de productos digitales y captación de leads desde redes sociales, en un único panel.

## Contenido

- `index.html` — página completa (HTML + CSS + JS mínimo, sin dependencias externas).
- `package.json` / `serve` — servidor estático mínimo para despliegue en Railway.

## Desarrollo local

Abre `index.html` directamente en el navegador, o sirve la carpeta:

```bash
npm install
npm start
```

## Despliegue en Railway

1. Crea un nuevo proyecto en Railway y selecciona **Deploy from GitHub repo**.
2. Elige este repositorio (`mi-CRM-vibeCoder`).
3. Railway detecta `package.json` automáticamente (Nixpacks), instala dependencias y ejecuta `npm start`, que sirve `index.html` en el puerto asignado por Railway (`$PORT`).
4. No se necesita configuración adicional ni variables de entorno.
