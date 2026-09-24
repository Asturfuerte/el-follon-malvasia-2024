# El Follón

Web estática del vino El Follón, Malvasía Volcánica 2024 de Lajares, Fuerteventura.

## Despliegue en Dokploy

- Tipo de construcción: Dockerfile
- Ruta del Dockerfile: `Dockerfile`
- Puerto interno: `80`
- No requiere variables de entorno
- No requiere base de datos

El contenedor usa Nginx y sirve directamente el contenido de `dist/`.

