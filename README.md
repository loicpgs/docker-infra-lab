# Docker Infra Lab

## Overview
This project is a complete Docker-based infrastructure lab designed to simulate a small production-like environment.

## Services
- Nginx
- Prometheus
- Grafana
- Node Exporter
- Portainer

## Goals
- Practice Docker Compose orchestration
- Deploy multiple services together
- Monitor infrastructure metrics
- Manage containers through a web interface

## Usage
Start the environment:

docker compose up -d

stop the environment:

docker compose down

## Access

Nginx: http://localhost:8080
Prometheus: http://localhost:9090
Grafana: http://localhost:3000
Node Exporter: http://localhost:9100/metrics
Portainer: https://localhost:9443


