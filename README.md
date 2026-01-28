
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=250&section=header&text=WeiLin%20Liu&fontSize=80&fontColor=ffffff&desc=Building%20Intelligent%20Systems%20%40%20Scale&descAlign=50&descAlignY=70" width="100%"/>
</div>

<div align="center">
  
  <a href="https://www.linkedin.com/in/weilinliu0410">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:willing.lau0.0@gmail.com">
    <img src="https://img.shields.io/badge/Email-willing.lau0.0@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/WillingLau">
    <img src="https://img.shields.io/badge/Status-Open%20To%20Work%20(Ireland)-2ea44f?style=for-the-badge" />
  </a>

  <br/><br/>
  
  <i>"I believe in <b>Strict Typing</b>, <b>Asynchronous Systems</b>, and <b>Progressive Overload</b> (in both code and gym)."</i>

</div>

---

## 👨‍💻 `config.py` (The Engineer Profile)

```python
from typing import List, Dict
from dataclasses import dataclass

@dataclass
class EngineerProfile:
    name: str = "WeiLin Liu"
    education: str = "MSc Computer Science @ UCD (Dublin)"
    coding_style: str = "Pythonic & Type-Safe (MyPy Enthusiast)"
    
    # Things I strictly avoid in production (and life):
    antipatterns: List[str] = [
        "Race Conditions", 
        "Hardcoded Secrets", 
        "Skipping Leg Day"
    ]
    
    current_focus: Dict[str, str] = {
        "Architecture": "RAG (Retrieval-Augmented Generation)",
        "Infrastructure": "AWS Serverless (Lambda/SQS)",
        "Optimization": "Reducing Inference Latency"
    }

    def daily_routine(self) -> str:
        return "Deploying Microservices ➜ Analyzing Vectors ➜ Lean Bulking (80kg goal)"

# Status Check
if __name__ == "__main__":
    print(EngineerProfile().daily_routine())

```

---

## 📊 Production Telemetry (Impact Log)

> *Forget the buzzwords. Here are the metrics from my actual deployments.*

| Metric | Value | Context |
| --- | --- | --- |
| **Search Performance** | `MRR ▲ 35%` | Improved from 0.60 to 0.81 using Hybrid Search (Vector + Keyword) |
| **Cloud Costs** | `COST ▼ 40%` | Migrated legacy services to AWS Serverless architecture |
| **Inference Speed** | `Latency < 200ms` | Optimized cold starts via MyPy refactoring & memory tuning |
| **Data Quality** | `Recall@10: 89%` | Engineered a batch ingestion pipeline for cleaner embeddings |
| **Test Coverage** | `Cov: 90%+` | Strict PyTest suites for production CI/CD pipelines |

---

## 🏗️ The Lab (Featured Architecture)

### 1. [The Brain: AI Multi-Agent Forum](https://github.com/WillingLau/AI_Multi_Agent_Forum_Simulation_System)

*A simulation of social dynamics using autonomous agents.*

* **The Stack:** `LangGraph` • `Neo4j` • `AsyncIO`
* **Engineering Note:** Implemented **semantic caching** (0.92 threshold) to save API costs and reduce latency. Uses a connection pool design to handle high-concurrency agent interactions.

### 2. [The Eyes: DeepDoc Parser](https://github.com/WillingLau/Document_Parser)

*Solving the "Garbage In, Garbage Out" problem in RAG.*

* **The Stack:** `Deep Learning (OCR)` • `Layout Analysis` • `FastAPI`
* **Engineering Note:** Most parsers fail at tables. I built a custom pipeline to perform **Table Structure Recognition (TSR)**, ensuring complex PDF data is actually retrievable.

### 3. [The Body: Healthy Lifestyle Assistant](https://github.com/WillingLau/Healthy_Life_Style_Assistant)

*My personal RAG-powered fitness companion.*

* **The Stack:** `DeepSeek R1` • `Weaviate` • `Linear Regression`
* **Engineering Note:** Combines LLM reasoning with traditional ML. It predicts my weight trends based on 40k+ synthetic records while RAG handles the nutrition science.

---

## 🛠️ Infrastructure & Stack

<div align="center">

| **Core Logic & AI** | **Data & RAG** | **Cloud & DevOps** |
| :---: | :---: | :---: |
| ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) | ![Milvus](https://img.shields.io/badge/Milvus-00A1EA?style=for-the-badge&logo=milvus&logoColor=white) | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white) |
| ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) | ![Weaviate](https://img.shields.io/badge/Weaviate-FA3E6E?style=for-the-badge&logo=weaviate&logoColor=white) | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) |
| ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) | ![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=for-the-badge&logo=neo4j&logoColor=white) | ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white) |
| ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white) | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white) | ![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white) |
| ![LlamaIndex](https://img.shields.io/badge/LlamaIndex-121212?style=for-the-badge&logo=llamaindex&logoColor=white) | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) | ![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white) |

</div>

---

## 📡 Neural Activity (Code Habits)
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=WillingLau&layout=compact&theme=tokyonight&hide_border=true&hide=java" height="160" width="800"/>
</div>
<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=WillingLau&theme=tokyonight" width="800" />
</div>

<div align="center">
  <small>Designed by WeiLin Liu • <i>Dublin, Ireland</i> 🇮🇪</small>
</div>
