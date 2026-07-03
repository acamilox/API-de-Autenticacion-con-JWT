# API de Autenticación con JWT

FastAPI + PostgreSQL + JWT + Docker

## Endpoints

- `POST /auth/register` — Registro de usuario
- `POST /auth/login` — Inicio de sesión (retorna JWT)
- `GET /users/me` — Obtener perfil del usuario autenticado
- `GET /admin/users` — Listar usuarios (solo admin)

## Requisitos

- Docker y Docker Compose

## Instalación

```bash
git clone <repo-url>
cd "API de Autenticacion con JWT"
cp .env.example .env
docker-compose up --build
```

Documentación: `http://localhost:8000/docs`
