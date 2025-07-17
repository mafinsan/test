# test

This repository contains a basic Python environment set up using Docker Compose.

eigkpj-codex/prepare-docker-compose-files-for-python
The Docker configuration is located in the `docker/` directory, while all
application code lives under `app/`.
main
## Usage

1. Build the Docker image:
   ```bash
eigkpj-codex/prepare-docker-compose-files-for-python
   docker compose -f docker/docker-compose.yml build
   ```
2. Start an interactive Python shell:
   ```bash
   docker compose -f docker/docker-compose.yml run --rm python
   ```

The `app/` directory will be mounted inside the container at `/usr/src/app` so
any changes to files are reflected between the host and container.
 main
