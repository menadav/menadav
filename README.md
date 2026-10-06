# David Mena
 
**Software Engineer — Backend · Go · Microservices · Event-Driven Systems**
 
Software engineer focused on backend development with **Go**, **microservices** and **event-driven architectures** (Kafka, Docker), trained through
advanced project-based programming at **42 Barcelona** with a strong low-level foundation in C and Linux. Also experienced
in Python and AI tooling: agentic frameworks, RAG pipelines and deterministic LLM decoding. Brings years of team
coordination and turn management in high-pressure airport operations — used to reliability, deadlines and systems that can't fail.
 
<p align="center">
  <a href="https://www.linkedin.com/in/menadav/">
    <img src="https://img.shields.io/badge/LINKEDIN-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
</p>
# 📂 Featured Projects
 
## 🐹 Backend & Distributed Systems (Go)
 
# [Kafka Microservice](https://github.com/menadav/REPO_KAFKA) — Event-Driven Microservice in Go
 
Event-driven microservice built in Go on top of **Apache Kafka**. Services communicate asynchronously through message queues — producers publish events to topics and consumer groups process them independently — decoupling components and allowing the system to scale and recover from failures without losing messages.
 
![Go](https://img.shields.io/badge/GO-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white) ![Kafka](https://img.shields.io/badge/APACHE_KAFKA-%23231F20.svg?style=for-the-badge&logo=apachekafka&logoColor=white) ![Docker](https://img.shields.io/badge/DOCKER-%232496ED.svg?style=for-the-badge&logo=docker&logoColor=white)
 
---
 
# [TAP — The Answer Protocol](https://github.com/menadav/TCP) — Real-Time Multiplayer TCP Protocol Engine
 
Custom line-based TCP protocol powering a shared-world multiplayer text adventure, built from scratch in Go with a central-hub concurrency model and zero external dependencies for state management.
 
![Go](https://img.shields.io/badge/GO-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white) ![TCP](https://img.shields.io/badge/TCP-%23004482.svg?style=for-the-badge&logo=cloudflare&logoColor=white) ![Concurrency](https://img.shields.io/badge/CONCURRENCY-%23375EAB.svg?style=for-the-badge&logo=go&logoColor=white) ![Fyne](https://img.shields.io/badge/FYNE-%23FF8C00.svg?style=for-the-badge&logoColor=white)
 
---
 
## 🤖 AI Engineering (Python)
 
# [Agent Smith](https://github.com/Edugs94/agent_smith) — Sandboxed Coding Agent Framework *(with [Edugs94](https://github.com/Edugs94))*
 
Agentic framework that solves coding tasks in an iterative loop: the LLM writes Python, it runs in a **sandboxed subprocess**, and the output becomes the next observation. One architecture for both **MBPP** and **SWE-bench Verified** (real bug fixes in Docker containers).
 
- **Defense-in-Depth Sandbox:** Fork-then-restrict model with AST validation, restricted builtins, filesystem checks and resource limits.
- **MCP Tooling:** Tools exposed through the Model Context Protocol and called directly from model-written code.
- **Multi-Provider:** Mistral, Groq, Google AI Studio and OpenRouter, with automatic API key rotation on quota and rate limits.
- **Benchmarked:** 7 models across 4 providers, with ablation studies and a 100-test suite.

![Python](https://img.shields.io/badge/PYTHON-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white) ![Docker](https://img.shields.io/badge/DOCKER-%232496ED.svg?style=for-the-badge&logo=docker&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-%23000000.svg?style=for-the-badge&logoColor=white) ![Pydantic](https://img.shields.io/badge/PYDANTIC-%23E92063.svg?style=for-the-badge&logo=pydantic&logoColor=white)
 
---
 
# [RAG Against the Machine](https://github.com/menadav/IA_LLM_RAG) — Hybrid Search & Repository-Scale RAG
 
End-to-end RAG system designed to interact with large codebases, combining sparse and dense retrieval to provide accurate natural-language answers using the Qwen LLM.
 
- **Semantic Code Chunking:** Context-aware chunking strategies that preserve code logic across multiple files.
- **Hybrid Search Architecture:** Fuses BM25 lexical scoring with ChromaDB vector embeddings via Reciprocal Rank Fusion (RRF).
- **Evaluation Pipeline:** Built-in Recall@k evaluation suite to benchmark and optimize retrieval quality.
- **End-to-End CLI:** Command-line interface managing everything from data ingestion to answer generation.
  
![Python](https://img.shields.io/badge/PYTHON-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white) ![Transformers](https://img.shields.io/badge/TRANSFORMERS-%23FFD21E.svg?style=for-the-badge&logo=huggingface&logoColor=black) ![Pydantic](https://img.shields.io/badge/PYDANTIC-%23E92063.svg?style=for-the-badge&logo=pydantic&logoColor=white) ![ChromaDB](https://img.shields.io/badge/CHROMADB-%23FF4B4B.svg?style=for-the-badge&logo=googlecloud&logoColor=white)
 
---
 
# [Call Me Maybe](https://github.com/menadav/IA_LLM_Logit_Masking) — LLM Constrained Decoding
 
Deterministic LLM pipeline that guarantees **100% valid JSON function calls** by masking model-generated logits at the token level. Enforces strict type-matching against JSON Schema and custom stopping criteria during generation — zero retries, zero parsing failures.
 
![Python](https://img.shields.io/badge/PYTHON-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white) ![Transformers](https://img.shields.io/badge/TRANSFORMERS-%23FFD21E.svg?style=for-the-badge&logo=huggingface&logoColor=black) ![Pydantic](https://img.shields.io/badge/PYDANTIC-%23E92063.svg?style=for-the-badge&logo=pydantic&logoColor=white)
 
---
 
## ⚙️ Systems & Algorithms
 
# [Codexion](https://github.com/menadav/Threads) — Multithreading
 
Highly concurrent operating system simulation. Shared resource orchestration and CPU scheduling (FIFO/EDF) using POSIX threads and mutexes to prevent deadlocks.
 
![C](https://img.shields.io/badge/C-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
 
---
 
# [Fly-In](https://github.com/menadav/Test_Dijkstra) — Multi-Drone Routing Optimizer
 
Simulation engine that solves optimal multi-drone routing using **Time-Expanded Graphs**. Handles pathfinding, collision avoidance and capacity constraints — implemented from scratch without external graph libraries.
 
![Python](https://img.shields.io/badge/PYTHON-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white) ![Pytest](https://img.shields.io/badge/PYTEST-%230A9EDC.svg?style=for-the-badge&logo=pytest&logoColor=white) ![Pydantic](https://img.shields.io/badge/PYDANTIC-%23E92063.svg?style=for-the-badge&logo=pydantic&logoColor=white) ![Pygame](https://img.shields.io/badge/PYGAME-%23F15A24.svg?style=for-the-badge&logo=pygame&logoColor=white)
 
---
 
# [Pac-Man](https://github.com/menadav/Pac-Man) — Arcade Game Engine
 
Full recreation of the classic arcade game: MVC architecture, procedural maze generation, ghost AI with distinct behavioral personalities, and persistent highscores.
 
![Python](https://img.shields.io/badge/PYTHON-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white) ![Pydantic](https://img.shields.io/badge/PYDANTIC-%23E92063.svg?style=for-the-badge&logo=pydantic&logoColor=white) ![Pygame](https://img.shields.io/badge/PYGAME-%23F15A24.svg?style=for-the-badge&logo=pygame&logoColor=white)
 
# 🛠️ Technologies
 
<p align="center">
  <img src="https://img.shields.io/badge/GO-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white" alt="Go">
  <img src="https://img.shields.io/badge/APACHE_KAFKA-%23231F20.svg?style=for-the-badge&logo=apachekafka&logoColor=white" alt="Kafka">
  <img src="https://img.shields.io/badge/DOCKER-%232496ED.svg?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/PYTHON-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/C-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white" alt="C">
  <img src="https://img.shields.io/badge/MYSQL-%234479A1.svg?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/LINUX-%23FCC624.svg?style=for-the-badge&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/GIT-%23F05032.svg?style=for-the-badge&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/VS_CODE-%23007ACC.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VS Code">
</p>
 
