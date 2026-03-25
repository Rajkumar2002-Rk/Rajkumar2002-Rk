<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0e1a,100:3b82f6&height=120&section=header&animation=fadeIn" width="100%"/>

# Raj Kumar Nelluri
### AI / ML Engineer · LLM Systems · Production Deployment

<p align="center">
  <b>B.Tech AI · Amrita Vishwa Vidyapeetham &nbsp;|&nbsp; MS Computer Science · Pace University, New York</b><br/>
  I don't just build models — I ship AI systems that run in production on AWS.<br/>
  From RAG pipelines and LLM agents to computer vision and MLOps — full stack, end to end.
</p>

[![Portfolio](https://img.shields.io/badge/🌐%20Portfolio-rajkumarai.dev-0a0e1a?style=for-the-badge)](https://rajkumarai.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/raj-kumar-nelluri-351389393/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rajkumarn2002@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Rajkumar2002-Rk)
[![AWS Certified](https://img.shields.io/badge/AWS-Cloud%20Practitioner-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://rajkumarai.dev)

![Profile Views](https://komarev.com/ghpvc/?username=Rajkumar2002-Rk&style=for-the-badge&color=3b82f6)

</div>

---

<div align="center">

### 🚀 Systems Live in Production Right Now

| | Project | Live Demo | Stack |
|---|---|---|---|
| 🟣 | **AI Financial Research Agent** | [![Live](https://img.shields.io/badge/▶%20Live-fintel.rajkumarai.dev-brightgreen?style=flat-square)](https://fintel.rajkumarai.dev) | GPT-4o · FastAPI · AWS EC2 · Docker |
| 🔵 | **Enterprise RAG Chatbot** | [![Live](https://img.shields.io/badge/▶%20Live-chatbot.rajkumarai.dev-brightgreen?style=flat-square)](https://chatbot.rajkumarai.dev) | LangChain · ChromaDB · AWS EC2 · Docker |

</div>

---

## 🧑‍💻 About Me

I'm an AI/ML Engineer who ships production AI — not just prototypes. My work spans the full stack: LLM agents, RAG pipelines, computer vision, and cloud-native MLOps on AWS.

- 🤖 **LLM Engineering** — RAG pipelines, LangGraph agents, tool-calling, prompt engineering, OpenAI API
- 🔭 **End-to-end ML** — data ingestion → feature engineering → training → real-time inference → monitoring
- ☁️ **Cloud-native systems** — AWS EC2, S3, Lambda, Kinesis, SageMaker, RDS, EventBridge
- 👁️ **Computer Vision** — YOLOv8 object detection, ResNet-50 classification, 50ms inference APIs
- 📊 **MLOps** — data drift detection, automated retraining, MLflow, CloudWatch, GitHub Actions CI/CD
- 🎓 **AWS Certified Cloud Practitioner** · MS CS, Pace University, New York

> *"A model that doesn't reach production is a prototype, not a solution."*

---

## 📊 Results That Matter

<div align="center">

| Metric | Result | Project |
|---|---|---|
| 🎯 Fraud Detection Accuracy | **96.7%** on 50k+ claims | Insurance Fraud Detection |
| 📈 Churn Prediction F1 | **91% accuracy / 89% F1** | Customer Churn + MLOps |
| 🔍 RAG Retrieval Accuracy | **87%** on benchmark queries | Enterprise RAG Chatbot |
| 📉 Sales Forecast RMSE | **4.2%** — 18% better than baseline | Retail Sales Forecasting |
| ⚡ Report Generation | **< 30 seconds** end-to-end | AI Financial Research Agent |
| 🧠 Inference Latency | **50ms** real-time | Insurance Fraud Detection |

</div>

---

## 🚀 Featured Projects

---

### 🟣 AI Financial Research Agent — [Live Demo ↗](https://fintel.rajkumarai.dev) · [GitHub ↗](https://github.com/Rajkumar2002-Rk/financial-research-agent)

> *Autonomous GPT-4o agent that generates structured BUY/HOLD/SELL investment reports in under 30 seconds*

Most AI financial tools let the LLM decide whether to buy or sell. This system does not. The investment decision is made entirely by a **deterministic scoring engine** — GPT-4o only explains the decision in plain English. This eliminates hallucination from the most critical part of the pipeline.

```
User Request → FastAPI → LangGraph Agent → Market Data (Stooq) + Fundamentals (Alpha Vantage) + News (Tavily)
     → Deterministic Scoring Engine (Technical + Fundamental + Sentiment)
     → Conflict Detection → Confidence Model → BUY / HOLD / SELL
     → GPT-4o Explanation → Redis Cache → JSON Response → Dark UI
```

**Key innovations:** Normalised scoring (missing data not penalised) · Conflict detection override · 5-factor confidence model · Portfolio ranking mode · Time-horizon weight profiles · Redis caching (10× API cost reduction)

`Python` `FastAPI` `LangGraph` `GPT-4o` `Alpha Vantage` `Tavily` `Redis` `Docker` `AWS EC2`

---

### 🔵 Enterprise RAG Chatbot — [Live Demo ↗](https://chatbot.rajkumarai.dev) · [GitHub ↗](https://github.com/Rajkumar2002-Rk/rag-chatbot)

> *Production RAG pipeline — 87% retrieval accuracy, hallucination guardrails, live on AWS EC2*

Full production RAG system: MMR retrieval for result diversity, metadata-injected citations, session-isolated upload mode, structured JSON logging, and real-time streaming. Every response includes `[SOURCE N: filename | Page]` — zero hallucinations.

```
PDF (Library or Upload) → PyPDF → Chunking (1000/200 overlap)
     → OpenAI Embeddings (text-embedding-3-small) → ChromaDB
     → MMR Retrieval (fetch_k=20, top-5) → Hallucination Guardrail
     → Strict Prompt + Citations → GPT-3.5-turbo → Streamlit Streaming UI
```

**Key innovations:** Similarity threshold guardrail · MMR diversity retrieval · Metadata citation injection · Upload-any-PDF mode · Session-isolated temp vectorstore · Structured query logging

`Python` `LangChain` `OpenAI API` `ChromaDB` `Streamlit` `Docker` `AWS EC2` `PyPDF`

---

### 🔴 Insurance Fraud Detection — [GitHub ↗](https://github.com/Rajkumar2002-Rk)

> *Dual-model CV pipeline — 96.7% accuracy on 50k+ insurance claims at 50ms inference*

YOLOv8 localises vehicle damage in real time. ResNet-50 classifies severity and flags fraud indicators. Served via FastAPI at 50ms average inference latency on a cloud-native AWS pipeline.

`YOLOv8` `ResNet-50` `PyTorch` `OpenCV` `FastAPI` `AWS S3` `Lambda` `Kinesis` `SageMaker` `RDS`

---

### 🟢 Retail Sales Forecasting — [GitHub ↗](https://github.com/Rajkumar2002-Rk/aws-sales-forecasting)

> *LSTM + Prophet ensemble — 4.2% RMSE, 18% better than single-model baselines on AWS SageMaker*

Engineered a batch ETL pipeline processing 500K+ retail transactions. LSTM captures complex temporal patterns; Prophet handles seasonality and holidays. Deployed as a SageMaker real-time endpoint with automated weekly retraining from S3.

`LSTM` `Prophet` `PyTorch` `SageMaker` `S3` `Pandas` `NumPy`

---

### 🟡 Customer Churn Prediction — [GitHub ↗](https://github.com/Rajkumar2002-Rk/Customer_Chrun_Prediction)

> *MLOps pipeline — 91% accuracy, SHAP explainability, automated CI/CD retraining*

XGBoost classifier with 21 engineered features including NLP-extracted signals from support tickets. CloudWatch + EventBridge triggers automated model retraining on data drift. MLflow tracks all experiments.

`XGBoost` `SHAP` `MLflow` `AWS Comprehend` `CloudWatch` `EventBridge` `Docker` `GitHub Actions`

---

### 🟠 Crypto Price Forecasting — [GitHub ↗](https://github.com/Rajkumar2002-Rk)

> *Multi-model ML system — LSTM vs CNN vs XGBoost benchmarked on 7-day Bitcoin forecasting*

Benchmarked three architectures on held-out test data. XGBoost achieved best generalisation (lowest MAE and RMSE). Deployed as a Flask REST API with a live web dashboard at sub-second latency.

`XGBoost` `TensorFlow` `LSTM` `CNN` `Flask` `REST API` `Python`

---

### 🔮 3D Face Generation with NeRF — [GitHub ↗](https://github.com/Rajkumar2002-Rk)

> *Deformable NeRF for photorealistic 3D face reconstruction — 30%+ GPU memory reduction*

Implemented Deformable NeRF for photorealistic 3D reconstruction from monocular video. Reduced GPU memory by 30%+ through optimised batch rendering. Evaluated with PSNR across multiple synthesised viewpoints.

`JAX` `TensorFlow` `OpenCV` `COLMAP` `NeRF` `Python`

---

## ⚙️ Tech Stack

**Programming**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Generative AI & LLM**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
`LangGraph` `RAG Pipelines` `Vector Databases` `Prompt Engineering` `Embeddings` `Tool Calling`

**Machine Learning & CV**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square&logoColor=white)
`YOLOv8` `ResNet-50` `LSTM` `Prophet` `SHAP`

**Cloud & Infrastructure**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
`EC2` `S3` `SageMaker` `Lambda` `Kinesis` `RDS` `CloudWatch` `EventBridge`

**MLOps & Tools**
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
`Weights & Biases` `Jupyter` `Linux` `Bash`

---

## 🌱 Currently Building

- 🔧 **AI Resume Analyzer** — LLM-powered resume scoring and feedback system
- 🔍 **Semantic Search Engine** — production vector search with re-ranking and RAGAS evaluation
- 🤖 **Advanced RAG** — multi-modal RAG with images and tables, hybrid retrieval
- ⚙️ **Advanced MLOps** — model versioning, experiment tracking, CI/CD for ML
- 📡 **Large-Scale Pipelines** — Apache Spark, AWS Glue, real-time streaming architectures

---

## 📈 GitHub Activity

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=Rajkumar2002-Rk&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D)](https://github.com/Rajkumar2002-Rk)

</div>

<div align="center">

[![Raj's GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=Rajkumar2002-Rk&theme=tokyo-night&hide_border=true&area=true)](https://github.com/Rajkumar2002-Rk)

</div>

---

## 🔗 Let's Connect

I'm actively seeking **AI/ML Engineer**, **LLM Engineer**, and **Applied AI** roles at US tech companies and startups.

<div align="center">

| | |
|---|---|
| 🌐 **Portfolio** | [rajkumarai.dev](https://rajkumarai.dev) |
| 💼 **LinkedIn** | [linkedin.com/in/raj-kumar-nelluri](https://www.linkedin.com/in/raj-kumar-nelluri-351389393/) |
| 📧 **Email** | [rajkumarn2002@gmail.com](mailto:rajkumarn2002@gmail.com) |
| 🐙 **GitHub** | [github.com/Rajkumar2002-Rk](https://github.com/Rajkumar2002-Rk) |

</div>

---

<div align="center">
  <sub>✅ Available immediately &nbsp;·&nbsp; 🇺🇸 US-based (OPT / STEM OPT) &nbsp;·&nbsp; Open to remote & on-site roles</sub>
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3b82f6,100:0a0e1a&height=80&section=footer" width="100%"/>
