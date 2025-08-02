# ironsofts-observability

Stack de monitoreo de logs con Loki, Promtail y Grafana

---

## Español

Este proyecto levanta un stack de monitoreo de logs usando Docker Compose con Loki, Promtail y Grafana.

Este proyecto te permite implementar fácilmente una pila completa para recopilar todos los registros de tus servicios de Docker y visualizarlos centralmente en Grafana. Simplemente carga (clona) el proyecto, ejecútalo y tendrás acceso a todos los registros de tus contenedores desde una interfaz web.

### Servicios

- **Loki:** Recolector y almacén de logs.
- **Promtail:** Agente que recoge los logs desde contenedores Docker.
- **Grafana:** Dashboard web para visualizar y consultar los logs.

### Requisitos previos

- Docker y Docker Compose instalados.

### Instrucciones

1. Clona este repositorio y navega a la carpeta `ironsofts-observability`:
   ```bash
   git clone https://github.com/ironsofts/ironsofts-observability.git
   cd ironsofts-observability
   ```
2. (Opcional) Crea un archivo `.env` para personalizar los puertos si lo deseas.
3. Levanta los servicios:
   ```bash
   docker-compose up -d
   ```
4. Accede a Grafana en: [http://localhost:3000](http://localhost:3000) (usuario y contraseña por defecto: `admin`/`admin`).

## Mantenimiento

Este repositorio es mantenido por **Gregorio Bolivar**, CEO de la empresa Ironsofts.

---

## English

This project deploys a log monitoring stack using Docker Compose with Loki, Promtail, and Grafana.

This project allows you to easily deploy a complete stack to collect all logs from your Docker services and view them centrally in Grafana. Just upload (clone) the project, run it, and you will have access to all your container logs from a web interface.

---

### Services

- **Loki:** Log collector and storage.
- **Promtail:** Agent that collects logs from Docker containers.
- **Grafana:** Web dashboard to visualize and query logs.

### Prerequisites

- Docker and Docker Compose installed.

### Instructions

1. Clone this repository and go to the `ironsofts-observability` folder:
   ```bash
   git clone https://github.com/ironsofts/ironsofts-observability.git
   cd ironsofts-observability
   ```
2. (Optional) Create a `.env` file to customize ports if needed.
3. Start the services:
   ```bash
   docker-compose up -d
   ```
4. Access Grafana at: [http://localhost:3000](http://localhost:3000) (default user and password: `admin`/`admin`).

---

## Maintainer

This repository is maintained by **Gregorio Bolivar**, CEO of Ironsofts.
