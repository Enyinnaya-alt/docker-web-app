# Docker Web Application

A simple Dockerized Node.js web application for testing DevOps deployment scripts.

## Features

- 🐳 **Dockerized** - Complete containerization
- 🌐 **Web Interface** - Beautiful responsive UI
- 🔧 **REST API** - Multiple endpoints for testing
- 🏥 **Health Checks** - Application monitoring
- 📊 **System Info** - Runtime information
- 🔒 **Security** - Non-root user in container

## API Endpoints

- `GET /` - Web interface
- `GET /health` - Health status
- `GET /api/info` - System information
- `GET /api/greet/:name` - Greeting API

## Quick Start

### Using Docker Compose

```bash
docker-compose up -d
