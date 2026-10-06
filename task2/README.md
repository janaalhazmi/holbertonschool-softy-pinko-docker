# Docker - Task 2: Front-end

## Description

This task adds a front-end to the Softy Pinko Docker project.

The back-end from Task 1 is moved into a `back-end` directory, and a new front-end is added using Nginx.

The front-end is served on port `9000`.

## Directory Structure

```text
task2/
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