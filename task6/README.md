# Docker - Task 6: Load Balancing

## Description

This task scales the Softy Pinko back-end to multiple API servers.

Docker Compose runs two back-end containers, while the Nginx proxy distributes requests between them.

## Directory Structure

```text

task6/

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

├── docker-compose.yml

│

└── 2-api-servers.txt