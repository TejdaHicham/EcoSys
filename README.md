# EcoSys

## Description

This Docker ecosystem comprises Apache Atlas, Apache NiFi, Apache Kafka, and Apache Zookeeper, configured to work together seamlessly. This setup is ideal for data governance, data flow management, and data streaming scenarios.

## Prerequisites

- Docker Engine installed on your machine.
- Docker Compose installed on your machine.

## Quick Start

1. Clone this repository:

   ```bash
   git clone https://github.com/TejdaHicham/EcoSys

2. Navigate to the project directory:
   ```bash
   cd EcoSys

3. Start the Docker containers:
   ```bash
   docker compose -f "docker-compose.yaml" up -d --build
   
## Access the services:

- Apache Atlas: http://localhost:21000
- Apache NiFi: https://localhost:8080
- Apache Kafka: http://localhost:9092
- Apache Zookeeper: http://localhost:2181

## Usage
- Use Apache Atlas for data governance, metadata management, and lineage tracking.
- Use Apache NiFi for data ingestion, transformation, and routing.
- Use Apache Kafka for building real-time data pipelines and streaming applications.
- Use Apache Zookeeper for distributed coordination and synchronization.
