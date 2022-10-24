# Dockerize RabbitMQ
Dockerize RabbitMQ

## Installation
```bash
# Run OCI Image
docker compose up -d

# (Optional) Recreate Run OCI Image
docker compose up --build --force-recreate -d
```
## Access RabbitMQ
```bash
Wait 1-2 minutes, until RabbitMQ UI ready to use!

<your_ip>:15672
```