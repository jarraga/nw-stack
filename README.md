# Northwind Demo Stack

Stack completo para levantar la demo de Northwind usando repositorios separados para backend y frontend.

## Uso

1. Copiar `.env.example` a `.env`:

   ```sh
   cp .env.example .env
   ```

2. Editar las variables en `.env` si hace falta.

3. Levantar el stack:

   ```sh
   docker compose up --build
   ```

## URLs

- Frontend: http://localhost:3000
- Backend: http://localhost:8080

## Comandos útiles

```sh
docker compose down
docker compose down -v
docker compose logs -f backend
docker compose logs -f frontend
docker compose logs -f db
```

## Notas

- El backend se construye desde `https://github.com/jarraga/nw-back.git#main`.
- El frontend se construye desde `https://github.com/jarraga/nw-front.git#main`.
- No se incluyen secretos reales. Usar `.env` para valores locales.
- No se incluye código de backend ni frontend en este repositorio.
