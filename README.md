# FastAPI-App

This repository contains a skeleton for a Dockerized FastAPI application. FastAPI is a modern, fast (high-performance) web framework for building APIs with Python 3.7+ based on standard Python type hints. This skeleton sets up a basic structure for your FastAPI app, using Docker for containerization, making it easy to develop, deploy, and scale.


## Features

- FastAPI: A high-performance framework for building APIs.
- Docker: Containerization for easy deployment and scaling.
- Uvicorn: A lightning-fast ASGI server for running your FastAPI app.

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

- Docker: Install Docker

- Docker Compose: Install Docker Compose

## Getting Started

### 1. Cloning the Repository

Clone this repository to your local machine:

```bash
git clone https://github.com/BioDani/FastAPI-App.git
cd FastAPI-App
```

### 2. Environment Variables

Create a environment

```bash
python -m venv app-env
```

Activate the environment

```bash
source app-env/bin/activate
```

Activate the environment

```bash
source app-env/bin/activate
```

Deactivate the environment

```bash
deactivate
```
Install packages into created environment

```bash
python -m pip install -r requirements.txt
```

### 3. Run the app without Docker

```bash
uvicorn app.main:app --port 8000 --reload
```

The FastAPI application will be available at http://localhost:8000.


### 4. Building and Running the Application (Docker)

Build the Docker image:

```bash


```

Run the Docker containers:


```bash

```


### 4. Stopping the Application

To stop the running containers:

```bash

```

### 5. Building and Running the Application



