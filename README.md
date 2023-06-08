# Kong Initial Steps

This repository contains the necessary files to set up a Kong API Gateway instance using Docker Compose and a custom configuration file.

## Prerequisites
- Docker
- Docker Compose

## Getting Started

1. Clone the repository:
   ```shell
   git clone https://github.com/vitoraderaldo/kong-initial-steps.git
   ```
2. Navigate to the repository directory:
    ```shel
    cd kong-initial-steps
    ```
3. Build and start the Kong API Gateway container:
    ```shel
    docker-compose up --build
   ```

4. You can test the proxied services at http://localhost:8000/api/products
