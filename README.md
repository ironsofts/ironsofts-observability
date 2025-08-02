# ironsofts-observability

Stack de monitoreo de logs con Loki, Promtail y Grafana

## Español

Este proyecto levanta un stack de monitoreo de logs usando Docker Compose con Loki, Promtail y Grafana.

### Servicios

- **Loki:** Recolector y almacén de logs.
- **Promtail:** Agente que recoge los logs desde contenedores Docker.
- **Grafana:** Dashboard web para visualizar y consultar los logs.

### Requisitos previos

- Docker y Docker Compose instalados.

### Instrucciones

1. Clona este repositorio y navega a la carpeta `ironsofts-observability`:
   ```bash
   git clone <REPO_URL>
   cd ironsofts-observability
   ```
2. (Opcional) Crea un archivo `.env` para personalizar los puertos si lo deseas.
3. Levanta los servicios:
   ```bash
   docker-compose up -d
   ```
4. Accede a Grafana en: [http://localhost:3000](http://localhost:3000) (usuario y contraseña por defecto: `admin`/`admin`).

---

## English

This project deploys a log monitoring stack using Docker Compose with Loki, Promtail, and Grafana.

### Services

- **Loki:** Log collector and storage.
- **Promtail:** Agent that collects logs from Docker containers.
- **Grafana:** Web dashboard to visualize and query logs.

### Prerequisites

- Docker and Docker Compose installed.

### Instructions

1. Clone this repository and go to the `ironsofts-observability` folder:
   ```bash
   git clone <REPO_URL>
   cd ironsofts-observability
   ```
2. (Optional) Create a `.env` file to customize ports if needed.
3. Start the services:
   ```bash
   docker-compose up -d
   ```
4. Access Grafana at: [http://localhost:3000](http://localhost:3000) (default user and password: `admin`/`admin`).
