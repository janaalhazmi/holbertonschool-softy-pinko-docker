# Docker - Task 3: Connect Front-end and Back-end

## Description

This task connects the front-end and back-end of the Softy Pinko Docker project.

The back-end uses Flask-CORS, and the front-end retrieves data from the API using AJAX.

## Directory Structure

```text
task3/
├── back-end/
│   ├── Dockerfile
│   ├── api.py
│   └── README.md
│
└── front-end/
    ├── Dockerfile
    ├── softy-pinko-front-end.conf
    └── softy-pinko-front-end/
        ├── assets/
        └── index.html