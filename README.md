## Synology NAS Monitoring System

#### Overview
This monitoring system allows you to collect and visualize various metrics from your Synology NAS, including CPU usage, memory usage, disk status, RAID status, etc. The system uses SNMP (Simple Network Management Protocol) to collect data from the NAS, Prometheus for storing time-series data, and Grafana for creating dashboards and visualizations. The system is containerized using Docker and uses Nginx as a reverse proxy. The system can be run directly on the NAS itself as Docker containers, however my goal was to host it on a remote Linux virtual machine.

![Synology NAS Dashboard](./images/synology_dashboard.png)
