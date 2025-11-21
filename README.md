# Cross-Platform Monitoring Infrastructure

A monitoring setup for Windows Server and Ubuntu VMs using industry-standard monitoring tools. This project demonstrates how to configure and deploy monitoring solutions across different operating systems.

## Overview

This project sets up monitoring infrastructure for both Windows Server and Ubuntu virtual machines. The goal is to monitor system health metrics (CPU, memory, disk) and configure alerts for proactive system management.

## What's Included

- **Infrastructure Setup**: Configuration for Windows Server and Ubuntu VM deployment
- **Monitoring Tools**: Configurations for Zabbix, Nagios, or Prometheus/Node Exporter
- **Alert Configuration**: CPU, memory, and disk usage alerts
- **Documentation**: Architecture write-up and setup guides
- **Screenshots**: Monitoring dashboard examples

## Project Structure

```
├── configs/          # Monitoring tool configuration files
├── docs/             # Documentation and architecture notes
├── infrastructure/   # Infrastructure-as-code files
├── scripts/          # Setup and deployment scripts
└── screenshots/      # Dashboard screenshots
```

## Getting Started

1. Deploy Windows Server and Ubuntu VMs
2. Install your chosen monitoring tool (Zabbix, Nagios, or Prometheus/Node Exporter)
3. Apply the configuration files from the `configs/` directory
4. Configure alerts as needed
5. Verify systems are reporting health metrics

## Notes

This is a work-in-progress setup for learning and demonstrating cross-platform monitoring capabilities. Config files and screenshots will be added as the project progresses.

