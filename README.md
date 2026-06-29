# 🔬 AI Scientific Discovery Platform

> An intelligent research assistant that leverages Generative AI, Knowledge Graphs, RAG, and Graph Neural Networks to accelerate scientific discovery.

[![Python Version](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/)
[![React Version](https://img.shields.io/badge/react-18.0+-blue.svg)](https://reactjs.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.100+-green.svg)](https://fastapi.tiangolo.com/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

---

## 📋 **Table of Contents**
- [🎯 Mission](#-mission)
- [✨ Key Features](#-key-features)
- [🏗️ Architecture](#️-architecture)
- [📊 Tech Stack](#-tech-stack)
- [🚀 Quick Start](#-quick-start)
- [📁 Project Structure](#-project-structure)
- [📚 API Documentation](#-api-documentation)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---

## 🎯 **Mission**

Transform scientific research by providing an AI-powered platform that:
- 🤖 **Generates** novel research hypotheses
- 🧪 **Designs** experiments automatically
- 🕸️ **Connects** scientific knowledge through graphs
- 📚 **Retrieves** relevant research context
- 📊 **Ranks** discoveries by potential impact
- 💡 **Explains** research outcomes clearly

---

## ✨ **Key Features**

### 🧠 **Intelligent Hypothesis Generation**
- Powered by Gemini API for state-of-the-art language understanding
- Domain-specific hypothesis suggestions
- Confidence scoring and reasoning
- Research gap identification

### 🔬 **Automated Experiment Design**
- Protocol generation based on hypotheses
- Methodology suggestions
- Variable identification and control
- Equipment recommendations

### 🕸️ **Knowledge Graph Visualization**
- Interactive concept networks
- Relationship exploration
- Semantic search across connected data
- Time-based evolution tracking

### 📚 **RAG-Powered Research**
- Intelligent document retrieval
- Context-aware responses
- Cited source attribution
- Large-scale document summarization

### 📊 **GNN Discovery Ranking**
- Impact prediction using graph neural networks
- Pattern recognition from historical research
- Emerging trend identification
- Similar discovery recommendations

---

## 🏗️ **Architecture**


---

## 📊 **Tech Stack**

### **Backend**
| Technology | Purpose |
|------------|---------|
| **FastAPI** | Web framework |
| **Python 3.10+** | Programming language |
| **PostgreSQL** | Relational database |
| **Neo4j** | Graph database |
| **Redis** | Caching & task queue |
| **Gemini API** | LLM integration |
| **PyTorch** | GNN implementation |
| **LangChain** | RAG framework |
| **FAISS** | Vector similarity search |
| **NetworkX** | Graph analysis |

### **Frontend**
| Technology | Purpose |
|------------|---------|
| **React 18** | UI framework |
| **TailwindCSS** | Styling |
| **Redux Toolkit** | State management |
| **D3.js** | Data visualization |
| **React Flow** | Graph visualization |
| **Chart.js** | Charts & analytics |
| **Axios** | API communication |
| **Vite** | Build tool |

### **DevOps**
| Technology | Purpose |
|------------|---------|
| **Docker** | Containerization |
| **GitHub Actions** | CI/CD |
| **Git** | Version control |

---

## 🚀 **Quick Start**

### **Prerequisites**
- Python 3.10+
- Node.js 16+
- PostgreSQL 14+
- Neo4j 5+
- Gemini API Key

### **Clone Repository**
```bash
git clone https://github.com/vishakha2121/AI-Scientific-Discovery-Platform.git
cd AI-Scientific-Discovery-Platform

cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
cp .env.example .env
# Edit .env file with your credentials

cd frontend
npm install
cp .env.example .env
# Edit .env file with backend URL