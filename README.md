# Sistema Beleza Pura – Entrega Final

Este repositório contém a entrega do projeto "Beleza Pura", incluindo os artefatos exigidos pela disciplina.

## ✅ Componentes do repositório

- `beleza-pura/` – Backend NestJS + banco PostgreSQL
- `beleza-pura-front/` – Frontend Web
- `docker-compose.yml` – Orquestração completa
- `docs/` – Proposta técnica, plano de testes e apresentação

## 🚀 Como executar

Certifique-se de ter o Docker e o Docker Compose instalados.

Usar .env para o postgres:
DATABASE_HOST=beleza_pura_postgres
DATABASE_PORT=5432
DATABASE_USER=user
DATABASE_PASSWORD=password
DATABASE_NAME=beleza_pura

Acesse:

Backend: http://localhost:3000

Frontend: http://localhost:5173

```bash
docker-compose up --build
