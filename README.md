# Simple Docker Web Server

This repository contains the necessary files to build and run a simple web server using Docker. It's designed as a demonstration to teach the basics of Docker.

## Prerequisites

- Docker installed on your machine. To install Docker, follow the instructions on the [[official Docker website](https://docs.docker.com/engine/install/).

## Repository Structure

- `Dockerfile`: A Dockerfile that defines the Docker image for the web server.
- `index.html`: The HTML file that will be served by the web server.

## Setup

To set up the web server, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Cyber-Courses/Simple-Python-Docker-Web-Server.git
   cd Simple-Python-Docker-Web-Server
   ```

2. **Build the Docker Image**:
   ```bash
   docker build -t mywebserver .
   ```

3. **Run the Docker Container**:
   ```bash
   docker run -p 8000:8000 mywebserver
   ```

After starting the container, you can access the web server by going to `http://localhost:8000` in your browser.
