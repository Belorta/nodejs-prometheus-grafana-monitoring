# DevOps Monitoring Stack (Node.js + Prometheus + Grafana)

A simple end-to-end observability project using Docker Compose.

## 🚀 Tech Stack
- Node.js (Express)
- Prometheus (Metrics scraping)
- Grafana (Visualization)
- Docker & Docker Compose

---

## 📊 Architecture
```text
Node.js App → Prometheus → Grafana Dashboard

---

## ⚙️ Features

- Exposes custom metrics using `prom-client`
- Scrapes metrics every 5 seconds
- Visualizes system metrics in Grafana
- Fully containerized using Docker Compose
- Service-to-service networking using Docker

---

## 🧪 Endpoints

- App: http://localhost:3002  
- Metrics: http://localhost:3002/metrics  
- Prometheus: http://localhost:9090  
- Grafana: http://localhost:3001  

---

## 🚀 Run Project

```bash
docker compose up --build

---

📈 Example Metrics
- process_resident_memory_bytes
- process_cpu_user_seconds_total

---

🎯 Learning Outcomes
- Monitoring & observability fundamentals
- Prometheus scraping model
- Grafana visualization
- Docker networking
- CI/CD ready structure (in progress)
