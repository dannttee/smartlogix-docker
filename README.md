# SmartLogix Docker Integration

Repositorio de integración para orquestar el frontend, el BFF y los microservicios con Docker Compose.

## Requisitos

- Docker Desktop instalado.
- Los repositorios clonados al mismo nivel:
  - smartlogix-frontend
  - smartlogix-bff
  - smartlogix-inventario-ms
  - smartlogix-pedidos-ms
  - smartlogix-docker

## Ejecución

Desde esta carpeta:

```bash
docker compose up --build -d
```

## Acceso

- Frontend: http://localhost:3000
- BFF: http://localhost:8080
- Inventario: http://localhost:8081
- Pedidos: http://localhost:8082
