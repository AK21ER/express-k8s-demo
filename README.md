# Express App with Docker & Kubernetes

This project demonstrates how to containerize and deploy a simple Express.js application using Docker and Kubernetes.

## Tech Stack
- Node.js / Express
- Docker
- Kubernetes

## Kubernetes Architecture
- Deployment: manages application pods and scaling
- Service: exposes the app and load-balances traffic
- ConfigMap: externalizes application configuration

## How to Run Locally
```bash
docker build -t express-demo .
docker run -p 3000:3000 express-demo

