# Docker - Task 4: Docker Compose

## Description

This task introduces Docker Compose to manage the Softy Pinko front-end and back-end services.

Docker Compose is used to build and run both containers together.

## Directory Structure

```text
task4/
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
└── docker-compose.yml