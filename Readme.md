# Keycloak Docker Compose Setup

This project contains a `docker-compose.yaml` file to quickly set up a Keycloak instance using Docker. 

## Features
- Runs the latest Keycloak image.
- Configurable admin username and password via environment variables (`ADMIN_USERNAME`, `ADMIN_PASSWORD`).
- Exposes Keycloak on port `8080` (default, configurable via `PORT`).

## Usage
1. Ensure Docker is installed.
2. Run `docker-compose up` to start Keycloak.
3. Access Keycloak at `http://localhost:8080`.
