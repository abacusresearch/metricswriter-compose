# metricswriter-compose

This repository provides a complete Docker-based setup for a new metrics service
that writes data to InfluxDB and visualizes it using Grafana. It includes:

- Docker configurations for InfluxDB and Grafana
- Predefined Grafana dashboards for immediate use

## Usage
### Requirements
[Install Docker Engine](https://docs.docker.com/engine/install/)
- docker
- docker-compose-plugin

### Run
```bash
docker compose up -d --wait
```

### Access
- Grafana: https://127.0.0.1:3000/
- InfluxDB: https://127.0.0.1:8086/

Get credentials from [compose.yaml](./compose.yaml).
