# test

This repository contains a basic Python environment set up using Docker Compose.

## Usage

1. Build the Docker image:
   ```bash
   docker compose build
   ```
2. Start an interactive Python shell:
   ```bash
   docker compose run --rm python
   ```

The current directory will be mounted inside the container at `/usr/src/app` so any changes to files are reflected between the host and container.
