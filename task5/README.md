# Docker - Task 5: Proxy Server

## Description

This task adds an Nginx proxy server to the Softy Pinko Docker project.

The proxy connects the front-end and back-end and provides a single entry point on port `80`.

## Directory Structure

```text

task5/

├── back-end/

│   ├── Dockerfile

│   ├── api.py

│   └── README.md

│

├── front-end/

│   ├── Dockerfile

│   ├── softy-pinko-front-end.conf

│   └── softy-pinko-front-end/

│       ├── assets/

│       └── index.html

│

├── proxy/

│   ├── Dockerfile

│   └── proxy.conf

│

└── docker-compose.yml