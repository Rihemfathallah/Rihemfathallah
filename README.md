<h1 align="center">Rihem Fathallah</h1> <h3 align="center">Telecom Engineering Student · AIOps</h3> <p align="center"> AIOps · LLM Agents · Kubernetes & GitOps · Observability · 5G Networks </p> <p align="center"> <a href="https://www.linkedin.com/in/rihem-fathallah-"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square" alt="LinkedIn"></a> <a href="mailto:rihem.fathallahengineer@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a> <img src="https://img.shields.io/badge/Open%20to-PFE%20Jan%202027-2EA44F?style=flat-square" alt="Open to PFE internship, February 2027"> </p>

## About

Final-year Telecommunications Engineering student at ENET'Com Sfax, focused on AIOps: using ML and LLM agents to run infrastructure.

- **Detect** - anomaly detection on infrastructure metrics.
- **Diagnose** - LLM agents that find the root cause from metrics, events and runbooks.
- **Remediate** - automated fixes and rollbacks, with human approval.

Looking for a 6-month end-of-studies (PFE) internship in AIOps / AI Engineering starting February 2027.

## Core Stack

`Python` `LangGraph` `MCP` `Mistral AI` `RAG` `ChromaDB` `RAGAS` `Kubernetes` `Docker` `Helm` `Terraform` `Argo CD` `GitHub Actions` `Prometheus` `Alertmanager` `Grafana` `Loki` `Chaos Mesh` `Scikit-learn` `PyTorch` `FastAPI` `Open5GS` `Linux`

## Experience

- **Generative AI Intern · Talan Tunisia (SummerCamp 2026), Tunis** - Agent layer (LangGraph, Mistral AI) of an urban-project design platform, with human validation at key decisions. Regulatory assistant with verifiable citations, ReAct agent with deterministic fallback, FastAPI background tasks with events persisted in SQLite and streamed to a React UI.
- **Summer Intern · Tunisie Telecom, Monastir** - Network department: fibre-optic network maintenance and troubleshooting of network anomalies.

## Selected Projects

- **NOC Copilot - AIOps on a cloud-native 5G core** - Anomaly detection (Isolation Forest, LSTM autoencoder) evaluated against a z-score baseline on labelled faults injected with Chaos Mesh and netem. A LangGraph agent then performs root-cause diagnosis using MCP tools (metrics, Kubernetes events) and runbooks served through NeuralRAG; remediation (restart, scaling) only after human approval. Runs on Open5GS and UERANSIM over k3s, monitored with Prometheus. *Code release in progress.*
- **Self-Healing GitOps Platform** - Terraform-provisioned Kubernetes cluster, Argo CD and Helm deployment, availability and latency SLOs with error-budget tracking, automated rollback on SLO alerts, disaster recovery with Velero (RTO / RPO measured). *Code release in progress.*
- [NeuralRAG](https://github.com/Rihemfathallah/NeuralRag) - Private-document RAG service with a local LLM, used as the workload and runbook engine of the two projects above: hybrid retrieval, ChromaDB, FastAPI. Shipped with Docker Compose, NGINX/HTTPS, Kubernetes manifests with HPA, GitHub Actions CI and a Prometheus / Loki / Grafana observability stack.
- [UrbanMind](https://github.com/Rihemfathallah/urban-mind) - Agent work from the Talan SummerCamp urban digital-twin project. Team repository: [Khatatli UrbanTwin](https://github.com/inesCherif/Khatatli_UrbanTwin).
- [Challenge Goal Analyzer](https://github.com/Rihemfathallah/ocr-challenge-goal-analyzer) - Streamlit dashboard built for the Talan SummerCamp hackathon: OCR on handwritten goals, then LLM analysis with structured outputs (LangChain, Gemini, Pydantic).
- **Topological Alert Correlation with GNNs** - Correlation of security alerts over the network topology using graph neural networks (PyTorch Geometric).


- [RIS-Assisted UAV Cognitive Radio](https://github.com/Rihemfathallah/ris-assisted-uav-cognitive-radio) - Deep reinforcement learning (TD3) for joint power and RIS phase control under an interference constraint, benchmarked against a convex optimisation bound. PyTorch, Stable-Baselines3, CVXPY. Full report in `report/`.
- **LLM Agent for Adaptive LoRa Modulation** - Link adaptation in hybrid terrestrial / LEO-satellite IoT networks. *Code release in progress.*

## Education & Certifications

- **ENET'Com Sfax** - Engineering Cycle in Telecommunications, 2024 - present
- **IPEIM Monastir** - Preparatory Cycle in Mathematics & Physics, 2022 - 2024
- Cisco CCNA - Switching, Routing, and Wireless Essentials
- Languages: Arabic (native) · French (B2) · English (B2)

## Contact

[LinkedIn](https://www.linkedin.com/in/rihem-fathallah-) · [GitHub](https://github.com/Rihemfathallah) · [Email](mailto:rihem.fathallahengineer@gmail.com)
<!--
**Rihemfathallah/Rihemfathallah** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
