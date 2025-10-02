# Enterprise Logging & Visualization Platform

## Overview
This repository is the starting point for designing and building an enterprise-wide 
logging and visualization platform. The goal of the project is to provide a 
secure, automated, and open-source-first solution for collecting, processing, 
and visualizing metrics, logs, and network flow data.

## Current Status
- 📌 Architectural design in progress (see `/docs/architecture-diagram.png`)
- 📌 Requirements gathered from project sponsor
- 🚧 Implementation not started yet

## Requirements (from sponsor)
- Open-source first stance
- Infrastructure as Code (IaC), versioned in GitLab
- Integration with "LibreNMS" (as a data source, not storage)
- Data ingestion via "Kafka" (no ZooKeeper, latest version)
- Collection of:
  - Syslog
  - Windows logs
  - Network flow data (NetFlow/IPFIX/sFlow via Akvorado)
  - Streaming telemetry from servers and network devices
- Storage in **ClickHouse** and/or **VictoriaMetrics**
- Visualization with **Grafana** (metrics/flows) and **Graylog** (logs)
- Secure, portable, and fully-redundant design

## Repository Layout (planned)

