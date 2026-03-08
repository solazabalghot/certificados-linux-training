# Entornos Docker del curso

Este directorio está pensado para los **escenarios Docker** que usarás en los laboratorios. Por defecto solo contiene este README.

**Los alumnos van creando las subcarpetas y los `docker-compose.yml`** según indique cada lab (por ejemplo `lab08-nginx`, `lab10-ansible`, etc.). Cada lab te guía para:

* Crear la subcarpeta correspondiente bajo `docker/`
* Añadir el `docker-compose.yml` y, si aplica, un `Dockerfile`
* Definir volúmenes a carpetas locales (`certs/`, `config/`, etc.) para editar en el host
* Levantar con `docker compose up -d` y usar `docker compose exec <servicio> bash` cuando necesites terminal en el contenedor

Convención detallada: [Lab 00 — Entorno con Docker Compose](../labs/lab00-entorno/03-entorno-docker-compose.md).
