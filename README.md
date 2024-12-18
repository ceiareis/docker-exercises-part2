# Docker Exercises - Part 2

This repository contains Docker Compose configurations and setup files for various services such as **Glances**, **Grafana**, **Heimdall**, **Node Exporter**, and **Prometheus**.

## Table of Contents

1. [Overview](#overview)
2. [Prerequisites](#prerequisites)
3. [Getting Started](#getting-started)

## Overview

This project is designed to provide a set of ready-to-use Docker Compose configurations for the following services:

- **Glances**: A cross-platform monitoring tool that provides a comprehensive overview of system resources.
- **Grafana**: A open-source analytics and monitoring platform used for visualizing time series data from various sources.
- **Heimdall**: A dashboard for organizing and accessing web applications and services.
- **Node Exporter**: A Prometheus exporter that collects hardware and OS metrics.
- **Prometheus**: An open-source systems monitoring and alerting toolkit used for recording real-time metrics in a time series database.

The configurations are set up with Docker Compose to allow easy setup and management of these services using Docker containers.

## Prerequisites

To use these Docker Compose configurations, you need to have the following tools installed:

- [Docker](https://www.docker.com/get-started) – A platform for developing, shipping, and running applications in containers.
- [Docker Compose](https://docs.docker.com/compose/install/) – A tool for defining and running multi-container Docker applications.

Make sure both Docker and Docker Compose are installed and running on your machine before proceeding.

## Getting Started

### 1. Clone the Repository

To get started, first clone this repository to your local machine:

```bash
git clone https://github.com/ceiareis/docker-exercises-part2.git
cd docker-exercises-part2 
```
## 2. Configure Docker Compose

Make sure you have the `docker-compose.yml` files in your local directory. These files define the necessary services and configurations.

## 3. Start Services

To start the services defined in the Docker Compose files, run the following command:

```bash
docker-compose up -d
```
## 4. Access the Services

After the containers are up and running, you can access the various services by navigating to the following ports:

- **Glances**: [http://localhost:61208](http://localhost:61208)
- **Grafana**: [http://localhost:3000](http://localhost:3000) (default credentials: `admin`/`admin`)
- **Heimdall**: [http://localhost:8080](http://localhost:"8080)
- **Prometheus**: [http://localhost:9090](http://localhost:9090)
- **Node Exporter**: [http://localhost:9100/metrics](http://localhost:9100/metrics)
  
 ## 5. Heimdall Setup
To setup the other services in the Heimdall dashboard, you need to access the dashboard, go to Application List, click add. From there you need to fill Application name and URL and then click save.

