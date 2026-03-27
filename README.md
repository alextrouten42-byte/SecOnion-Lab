# SecOnion-Lab

## Overview
This project demonstrates the design and implementation of a home cybersecurity lab using VirtualBox. The lab simulates enterprise network monitoring using:

- pfSense (Firewall)
- Security Onion (SIEM)
- Ubuntu Endpoint

## Architecture
- Lab Network: 10.1.1.0/24
- Home Network: 192.168.0.0/24

Traffic Flow:
Ubuntu → pfSense → Security Onion → Alerts

## Key Features
- Centralized log monitoring (20,000+ logs ingested)
- Syslog forwarding from pfSense
- Elastic Agent endpoint monitoring
- Segmented virtual network

## Technologies Used
- VirtualBox
- pfSense
- Security Onion
- Ubuntu 22.04
- Elastic Stack

## Lessons Learned
- Importance of network segmentation
- Firewall rule troubleshooting
- SIEM log ingestion pipeline
