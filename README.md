# Project Containers

Containerized development environments for personnal projects.

## Usage Pattern

Each project folder contains its own:

- `Dockerfile`
- `docker-compose.yml`
- project-specific `README.md`

To use a container, enter the project directory and follow its README.

## Notes

- Keep project containers isolated per directory.
- Reuse the same conventions (`.env`, user mapping, mounted sources) across projects.
