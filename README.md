# 🧠 IntelliMesh

**IntelliMesh** is a containerized, cloud-native frontend designed to explore AI-enhanced knowledge graphs through a visually intuitive Angular interface. It connects to AWS-hosted APIs that power back-end LLM-driven inference engines, enabling users to uncover relationships, hierarchies, and patterns within complex data ecosystems.

The platform includes **role-based access**, **responsive UI/UX**, and **interactive visual nodes** that allow analysts, researchers, and domain experts to dynamically query and visualize graph-based insights in real time.

## 📌 Features

- 🔗 **Knowledge Graph UI**:
  - Visual graph traversal with click-to-expand nodes
  - Contextual tooltips and metadata overlays
  - AI-inferred relationship highlighting

- 🔒 **Secure Access Controls**:
  - JWT-based role authentication (admin, analyst, viewer)
  - API gateway enforcement and session token expiry

- 🌐 **Cloud-Native Architecture**:
  - Deployed via Docker containers on AWS ECS
  - Angular-based SPA for responsive multi-device support

## 🧰 Tech Stack

- **Frontend**: Angular, D3.js, TypeScript
- **APIs**: AWS API Gateway, Lambda, Python (Flask/FastAPI)
- **AI Backends**: LLM-integrated inference layers
- **Deployment**: Docker, AWS ECS, Fargate

## 🚀 Getting Started

```bash
git clone https://github.com/your-username/intellimesh.git
cd intellimesh
docker-compose up --build
