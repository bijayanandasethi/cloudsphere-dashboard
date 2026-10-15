# ☁️ CloudSphere Enterprise DevOps Control Plane

![CloudSphere Banner](https://img.shields.io/badge/Status-Live_Production-emerald?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

> **Live Interactive Demo:** https://github.com/bijayanandasethi/cloudsphere-dashboard.git

---

## 🚀 Live Demo & Interface
Click the link above to explore the live control plane interface, featuring:
* **Real-time Cluster Telemetry**: Live CPU, Memory, and Pod health metrics.
* **Production Microservices Grid**: Active status monitoring for cluster workloads.
* **CI/CD Log Stream**: Interactive simulated pipeline execution console.
* **REST API Inspector**: Dedicated tab to inspect Node.js/Express endpoint JSON payloads.

---

## 🏗️ Multi-Tier Architecture & Folder Structure

```text
cloudsphere-dashboard/
├── backend/               # Node.js & Express REST API Service
│   ├── package.json       # Dependencies (Express, CORS)
│   └── server.js          # REST endpoints (/api/v1/health, /metrics)
├── frontend/              # Web Dashboard (Tailwind CSS, HTML5, JavaScript)
│   └── index.html         # Interactive Control Plane UI
├── Dockerfile             # Multi-stage container build setup
├── docker-compose.yml     # Local orchestration (Frontend + Backend API)
└── README.md              # Project documentation
