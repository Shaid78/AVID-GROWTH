# AVID-GROWTH

**Adaptive, Verified, Intelligent Decision System for Startup Viability, Diagnosis, Growth, and Strategic Planning**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![Node.js 18+](https://img.shields.io/badge/node.js-18+-green.svg)](https://nodejs.org/)

## 🚀 Overview

AVID-GROWTH is an **explainable adaptive multi-agent decision support framework** that assists entrepreneurs in evaluating startup viability, diagnosing business challenges, optimizing resource allocation, and generating strategic growth recommendations.

Unlike conventional startup evaluation platforms that rely on static questionnaires or black-box AI models, AVID-GROWTH integrates:
- **Adaptive Startup Classification** - Tailors assessment to each startup's unique characteristics
- **Dynamic Interview Generation** - Asks only relevant questions
- **19 Specialized AI Agents** - Each analyzing a specific business dimension
- **Knowledge & Reasoning Layer** - Ensures consistent, evidence-based recommendations
- **Explainability Module** - Every recommendation includes WHAT, WHY, HOW, WHO, WHEN, WHAT NEXT
- **Founder Coaching Mode** - Phased roadmaps with actionable implementation plans

## ✨ Features

- 🧬 **Startup DNA Analysis** - Radar chart visualization of 8 business dimensions
- 🕸️ **Relationship Mapping** - Interactive graph showing dimension dependencies
- 🔥 **Failure Propagation** - Cascading effect visualization
- 🔍 **Root Cause Analyzer** - Identifies underlying problems with evidence
- 👥 **Team Suitability Analyzer** - Current vs. required team assessment
- 📋 **Action Prioritization Board** - Ranked recommendations with cost/impact
- 🗺️ **Phased Roadmap** - 30/60/90 day implementation plans
- 🧠 **Explainability Panel** - Transparent reasoning for every recommendation

## 🏗️ Architecture
┌─────────────────────────────────────────────────────────────┐
│ Presentation Layer │
│ Next.js PWA + D3.js Visualizations │
├─────────────────────────────────────────────────────────────┤
│ Application Layer │
│ Chief Orchestrator Agent + Adaptive Interview Engine │
├─────────────────────────────────────────────────────────────┤
│ Business Logic Layer │
│ 19 Domain Intelligence Agents (Specialized) │
├─────────────────────────────────────────────────────────────┤
│ Knowledge Layer │
│ Business Rules | Knowledge Graph | Industry Benchmarks │
│ Historical Cases | Evaluation Rubrics | Confidence Rules │
├─────────────────────────────────────────────────────────────┤
│ Infrastructure Layer │
│ Docker | PostgreSQL | Redis | Ollama │
└─────────────────────────────────────────────────────────────┘



## 🛠️ Technology Stack

### Frontend
- Next.js 14 (React Framework)
- TypeScript
- Tailwind CSS
- D3.js (Visualizations)
- PWA (Progressive Web App)

### Backend
- Python 3.10+
- FastAPI
- SQLAlchemy
- Celery + Redis
- Ollama (Local LLM Inference)

### Database
- PostgreSQL 15 (with pgvector)
- Redis (Cache + Queue)

### DevOps
- Docker & Docker Compose
- GitHub Actions (CI/CD)
- Kubernetes (Deployment)

## 📦 Installation

### Prerequisites
- Node.js 18+
- Python 3.10+
- Docker & Docker Compose
- Git

### Quick Start with Docker

```bash
# Clone the repository
git clone https://github.com/yourusername/avid-growth.git
cd avid-growth

# Start all services
docker-compose up

# Access the application
# Frontend: http://localhost:3000
# Backend API: http://localhost:8000
# API Docs: http://localhost:8000/docs
