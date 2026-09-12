# Azure Agentic Platform

Open-source reference architecture for building production-ready AI agents on Microsoft Azure.

This project explores practical patterns for:

- Azure AI agents
- Microsoft Foundry
- Model Context Protocol (MCP)
- Tool calling
- Identity and security
- Agent evaluation
- OpenTelemetry and observability
- Azure Container Apps
- Azure Kubernetes Service (AKS)
- Grounded retrieval and RAG

## Goal

The goal is to move beyond AI agent demos and explore what it takes to build secure, observable, reliable, and scalable agentic applications on Azure.

## High-Level Architecture

```text
User
  |
  v
AI Agent
  |
  +--> Retrieval / Grounding
  |
  +--> MCP / Tools
  |
  v
Azure Services
  |
  v
Grounded Response

Security + Identity + Evaluation + Observability
```

## Roadmap

- v0.1 - Agent Foundation
- v0.2 - MCP Tool Layer
- v0.3 - Identity & Security
- v0.4 - AgentOps & Observability
- v0.5 - Event-Driven Agents
- v0.6 - Container Apps & AKS
- v0.7 - Enterprise Retrieval

## Author

**Hastimal Jangid**

Cloud, Data & AI Architect | Researcher | IEEE Senior Member

Website: https://hastimal.github.io  
GitHub: https://github.com/hastimal
