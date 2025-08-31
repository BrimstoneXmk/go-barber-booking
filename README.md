# Go Barber Booking ✂️

An end-to-end **microservices-based booking system** built with **Golang**.  
Designed as a learning project to practice:

- ⚡ Concurrency patterns in Go (worker pools, fan-out/fan-in, context cancellation)
- 🐳 Containerization with Docker
- ☸️ Orchestration with Kubernetes (Minikube for local dev)
- 🚀 CI/CD pipelines (GitHub Actions → Docker Registry → K8s deploy)
- 📊 Observability with Prometheus + Grafana

---

## 🎯 Project Goals
- Build a scalable booking system for barbershops
- Prevent double-bookings via concurrency-safe logic
- Showcase real-world DevOps practices end-to-end
- Open-source portfolio project for learning & interviews

---

## 🏗️ Planned Architecture
- **Customer Service** → user registration, booking history
- **Barber Service** → barber profiles & availability
- **Booking Service** → slot management, concurrency-safe booking
- **Notification Service** → async reminders via RabbitMQ
- **PostgreSQL** → persistent storage
- **RabbitMQ** → event-driven async messaging

---

## ⚡ Tech Stack
- Language: Go
- Database: PostgreSQL
- Message Broker: RabbitMQ
- Orchestration: Kubernetes (Minikube/Kind for local)
- Monitoring: Prometheus + Grafana
- CI/CD: GitHub Actions

---

## 🚀 Roadmap
- [ ] Define requirements & architecture
- [ ] Implement core microservices
- [ ] Containerize services with Docker
- [ ] Deploy locally on Minikube
- [ ] Add CI/CD pipeline
- [ ] Integrate monitoring & logging
- [ ] Stress test concurrency & scaling
