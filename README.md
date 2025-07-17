# GRS – Google Cloud Microservices Demo for E-Commerce (Project Report)

This repository contains the final report for our Graduate Systems (CSE-638) course project at IIIT-Delhi. The project explores Google Cloud’s microservices demo (Online Boutique), focusing on deployment, observability, and performance profiling.

📄 **[Download Report PDF](./report.pdf)**

---

## 📌 Project Summary

- **Goal:** Analyze and deploy a scalable microservices-based architecture using Kubernetes and Docker.
- **Platform:** Google Cloud Microservices Demo (Online Boutique)
- **Deployment:** Kubernetes (GKE and local cluster)
- **Observability:** Prometheus, Grafana, Kiali, WeaveScope
- **Load Testing:** Locust and Ngrok

---

## 🧪 Technologies Used

| Technology        | Purpose                            |
|------------------|------------------------------------|
| Docker           | Containerization                   |
| Kubernetes (GKE) | Orchestration                      |
| gRPC             | Inter-service communication        |
| Redis, Spanner   | Caching & storage                  |
| Prometheus       | Monitoring & metrics collection    |
| Grafana          | Visualization                      |
| Kiali, Weave     | Microservices traffic visualization|
| Locust, Ngrok    | Load testing and traffic simulation|

---

## 📊 Dashboards & Monitoring

Prometheus and Grafana were used to monitor:

- API latency, traffic, and node health
- CPU, memory, and network metrics
- Microservice traffic flow (via Kiali & WeaveScope)

---

## 📈 Load Testing Results

Simulated traffic using Locust for:
- 20 concurrent users: Stable performance
- 500 concurrent users: Spike in failure rates (19%), increased CPU usage

---

## 🧠 Learnings

- Implemented Helm-based observability setup
- Gained experience with Istio service mesh
- Visualized real-time traffic and service failures
- Applied best practices for microservices-based performance profiling

---

## 👨‍💻 Contributors

- MT24031 Deepankar Verma  
- MT24092 Siddhartha Vardhan  
- MT24057 Nakul Panwar  
- MT24122 Kanishk Saraswat

---

## 📚 References

- [Google Cloud Microservices Demo](https://github.com/GoogleCloudPlatform/microservices-demo)
- [Forked Repo (Our Work)](https://github.com/deepankar-MT24031/GRS_GOOGLE_PROJECT)
