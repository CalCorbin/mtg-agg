# mtg-agg (Magic the Gathering Aggregator)

Welcome to mtg-agg! This is a news aggregator for magic the gathering, powered by crawl4ai.

## Requirements
- Docker (Ensure Docker is installed on your system)

## Local Development Setup
1. Build the Docker image.
    - `docker build -t fastapi-app .`
2. Run the application.
   `docker compose up mtgapi`
3. Access the API docs.
   - Swagger UI: http://localhost:8000/docs
   - ReDoc: http://localhost:8000/redoc
4. Test the API.
    - `curl http://localhost:8000`