# Proyecto Docker: Plataforma de Tareas y Monitoreo

Este proyecto inicia un ecosistema de servicios con Docker Compose, ideal para monitoreo, gestión de tareas, visualización de métricas y manejo de API REST.

## Servicios incluidos

- **API REST Quarkus** – Gestión de tareas.
- **Grafana** – Visualización con plugins personalizados.
- **Prometheus** – Recolección de métricas.
- **NGINX** – Proxy reverso.
- **PostgreSQL** – Base de datos relacional.

## Requisitos previos

- Tener instalado [Docker Desktop](https://www.docker.com/products/docker-desktop).
- Descargar los archivos del proyecto en una carpeta local.

## Ejecutar el servicio

--docker-compose -f docker-compose.hub.yml up
