## 🛠️ Services

- **Service 1 (Go)** – Exposes a `/ping` route.
- **Service 2 (Python)** – Also exposes a `/ping` route.

## 🌐 Routing via NGINX

NGINX handles reverse proxying to these services:

- `localhost:8080/service1/ping` → Service 1
- `localhost:8080/service2/ping` → Service 2

## 🚀 Running the Setup

Start the containers:

```bash
docker-compose up --build
