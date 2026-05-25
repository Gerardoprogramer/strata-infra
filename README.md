# Strata Infrastructure

Production infrastructure for Strata platform.

## Services

- Nginx
- Next.js frontend
- FastAPI backend
- PostgreSQL

## Deploy

```bash
docker compose -f docker-compose.prod.yml pull
docker compose -f docker-compose.prod.yml up -d


---

# 6. Probar local

Dentro de `strata-infra`:

```bash id="y9m2pk"
docker compose -f docker-compose.prod.yml up