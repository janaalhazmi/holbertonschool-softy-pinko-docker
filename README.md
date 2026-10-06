# Docker - Softy Pinko

## Description

This project introduces Docker, Flask, Nginx, Docker Compose, proxy servers, and load balancing through a series of tasks.

## Tasks

### Task 0 - Docker Basics

Creates a basic Ubuntu Docker image that outputs `Hello, World!`.

### Task 1 - Back-end

Creates a Flask back-end with an `/api/hello` endpoint running on port `5252`.

### Task 2 - Front-end

Adds an Nginx front-end served on port `9000`.

### Task 3 - Connect Front-end and Back-end

Connects the front-end to the Flask API using AJAX and Flask-CORS.

### Task 4 - Docker Compose

Uses Docker Compose to manage the front-end and back-end services.

### Task 5 - Proxy Server

Adds an Nginx proxy that connects the front-end and back-end through port `80`.

### Task 6 - Load Balancing

Scales the back-end to two API servers and uses the Nginx proxy to distribute requests between them.

## Project Structure

```text
holbertonschool-softy-pinko-docker/
├── task0/
├── task1/
├── task2/
├── task3/
├── task4/
├── task5/
└── task6/