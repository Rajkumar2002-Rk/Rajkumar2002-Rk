<div align="center">

# Hi 👋 I'm Raj Kumar Nelluri

### AI Engineer · Machine Learning Engineer · Data Engineer

<p>
  B.Tech in Artificial Intelligence from Amrita Vishwa Vidyapeetham &nbsp;|&nbsp; MS Computer Science from Pace University, New York<br/>
  I build production-ready AI systems — from Generative AI and RAG pipelines to scalable ML workflows<br/>
  and cloud-native data engineering on AWS. Passionate about turning documents and raw data into intelligent, reliable AI products.
</p>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/raj-kumar-nelluri-351389393/)
[![Portfolio](https://img.shields.io/badge/Portfolio-0a0e1a?style=for-the-badge&logo=githubpages&logoColor=white)](https://rajkumar2002-rk.github.io/Real_Portfolio/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rajkumarn2002@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Rajkumar2002-Rk)

![Profile Views](https://komarev.com/ghpvc/?username=Rajkumar2002-Rk&style=for-the-badge&color=3b82f6)

</div>

---

## 🧑‍💻 About Me

I'm an AI and Machine Learning Engineer building **production-grade AI systems**, **Generative AI pipelines**, and **scalable data infrastructure** on AWS. My work spans the full AI stack — from RAG chatbots and vector databases to cloud-native ML pipelines and automated MLOps workflows.

- 🤖 I build **Generative AI systems**: RAG pipelines, LangChain, vector databases, prompt engineering, OpenAI API integration
- 🔭 I build **end-to-end ML pipelines**: data ingestion → feature engineering → model training → real-time inference → automated monitoring
- ☁️ I design **cloud-native data systems** using AWS S3, Lambda, Kinesis, SageMaker, RDS, and EventBridge
- 🧠 I apply **ML across domains**: fraud detection, churn prediction, demand forecasting, and computer vision
- 📊 I implement **MLOps practices**: data drift detection, automated retraining, CloudWatch monitoring, SageMaker managed training jobs
- 🎓 AWS Certified Cloud Practitioner · MS CS, Pace University, New York

> *"Good AI engineering is building systems that are accurate, reliable, and grounded in real data."*

---

## 🚀 What I Build

| Area | What I Do |
|---|---|
| **Generative AI** | RAG pipelines, LangChain chains, vector databases, prompt engineering, OpenAI API |
| **ML Pipelines** | End-to-end pipelines from raw data to real-time inference endpoints |
| **Data Engineering** | Batch and streaming ETL systems processing 500K+ records with schema validation |
| **Cloud ML Systems** | AWS-native architectures: S3 → Lambda → Kinesis → SageMaker → RDS |
| **MLOps & Monitoring** | Automated retraining triggers, data drift alerting, CloudWatch dashboards |
| **Model Development** | XGBoost, TensorFlow, Scikit-learn across classification, regression, and forecasting tasks |

---

## 📊 Featured Projects

### 🟣 Enterprise RAG Chatbot ⭐ Latest
> *Production-ready Retrieval-Augmented Generation chatbot with source citations*

Built a full RAG pipeline that answers questions from custom PDF documents accurately — with zero hallucinations on out-of-scope queries. The system converts documents into 195 semantic chunks, stores them as vector embeddings in ChromaDB, and retrieves the top-3 most relevant chunks using cosine similarity search to ground every GPT response in real document content.

**Stack:** `Python` `LangChain` `OpenAI API` `ChromaDB` `Streamlit` `PyPDF`
**Architecture:** PDF → PyPDF → Chunking (500/50) → OpenAI Embeddings → ChromaDB → Cosine Search → GPT-3.5-turbo → Cited Answer
**Key Results:** 195 chunks indexed · Multi-document querying · Zero hallucinations on out-of-scope questions · Page-level source citations

[![View Repo](https://img.shields.io/badge/GitHub-rag--chatbot-181717?style=flat-square&logo=github)](https://github.com/Rajkumar2002-Rk/rag-chatbot)

---

### 🔴 Insurance Fraud Detection System
> *Cloud-native, real-time fraud detection pipeline on AWS*

Built a distributed 4-stage fraud detection pipeline that processes insurance claims from ingestion to inference. Achieved approximately 90% classification accuracy on 15K+ records using XGBoost with engineered features.

**Stack:** `Python` `XGBoost` `Scikit-learn` `AWS S3` `Lambda` `Kinesis` `RDS` `SageMaker`
**Architecture:** S3 Data Lake → Lambda ETL → Kinesis Stream → SageMaker Inference → RDS Reporting

---

### 🔵 Customer Churn Prediction — MLOps Pipeline
> *End-to-end MLOps pipeline with NLP feature extraction and automated retraining*

Built an MLOps pipeline predicting SaaS customer churn using NLP-extracted features from 7K+ support tickets. Integrated CloudWatch + EventBridge for automated model retraining on data drift. Achieved 0.67 recall on the minority class.

**Stack:** `Python` `XGBoost` `AWS S3` `Lambda` `SageMaker` `Comprehend` `CloudWatch` `EventBridge`
**Architecture:** S3 → Lambda ETL → Comprehend NLP → SageMaker Training → CloudWatch + EventBridge Auto-Retrain

---

### 🟢 Retail Sales Forecasting on AWS
> *Scalable batch ETL pipeline for time-series demand forecasting*

Engineered a batch ETL pipeline processing 500K+ retail transactions with temporal feature extraction and lag-based predictors. Deployed as a SageMaker real-time inference endpoint serving live predictions.

**Stack:** `Python` `XGBoost` `Pandas` `NumPy` `AWS S3` `SageMaker`
**Architecture:** Raw Transactions → Python ETL → S3 Data Lake → SageMaker Job → Real-Time Endpoint

---

### 🟠 Crypto Price Forecasting — Flask REST API
> *Multi-model ML system with live web dashboard*

Benchmarked LSTM, CNN, and XGBoost on 7-day Bitcoin price forecasting. XGBoost achieved the best generalization on held-out test data (lowest MAE and RMSE). Deployed as a Flask REST API with a live web dashboard providing sub-second response latency.

**Stack:** `Python` `XGBoost` `TensorFlow` `LSTM` `CNN` `Flask` `REST API`
**Deployment:** Persistent REST endpoint with live dashboard

---

### 🟣 3D Face Generation with Neural Radiance Fields
> *Deformable NeRF for photorealistic 3D face reconstruction*

Implemented Deformable NeRF for photorealistic 3D face reconstruction from monocular video. Reduced GPU memory consumption by over 30% through optimized batch rendering. Evaluated with PSNR across multiple synthesized viewpoints.

**Stack:** `Python` `JAX` `TensorFlow` `OpenCV` `COLMAP` `NeRF`
**Result:** 30%+ GPU memory reduction · PSNR-evaluated multi-view synthesis

---

## ⚙️ Tech Stack

**Programming**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Generative AI**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
`RAG Pipelines` `Vector Databases` `Prompt Engineering` `Embeddings` `Semantic Search`

**Machine Learning**
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)

**Data Engineering**
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
`ETL Pipelines` `Batch Processing` `Stream Processing` `Schema Validation` `Data Quality`

**Cloud & MLOps**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
`S3` `SageMaker` `Lambda` `Kinesis` `RDS` `CloudWatch` `EventBridge` `Glue` `EC2` `IAM`

**Tools**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)

---

## 🌱 Currently Exploring

- **Generative AI Projects** — building AI Resume Analyzer, Semantic Search Engine, and AI Job Search Agent
- **Advanced RAG** — re-ranking, RAGAS evaluation framework, multi-modal RAG with images and tables
- **Advanced MLOps** — model versioning, experiment tracking, and CI/CD for ML systems
- **Large-Scale Data Pipelines** — Apache Spark, AWS Glue, and real-time streaming architectures
- **Cloud-Scale Vector Search** — Pinecone, Weaviate for production-grade vector databases

---

## 📈 GitHub Activity

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=Rajkumar2002-Rk&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D)](https://github.com/Rajkumar2002-Rk)

</div>

<div align="center">

[![Raj's GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=Rajkumar2002-Rk&theme=tokyo-night&hide_border=true&area=true)](https://github.com/Rajkumar2002-Rk)

</div>

---

## 🔗 Connect with Me

I'm actively seeking **AI Engineer**, **Applied AI Engineer**, **Machine Learning Engineer**, and **Data Engineer** roles at US tech companies and startups.

| | |
|---|---|
| 💼 **LinkedIn** | [linkedin.com/in/raj-kumar-nelluri](https://www.linkedin.com/in/raj-kumar-nelluri-351389393/) |
| 🌐 **Portfolio** | [rajkumar2002-rk.github.io/Real_Portfolio](https://rajkumar2002-rk.github.io/Real_Portfolio/) |
| 📧 **Email** | [rajkumarn2002@gmail.com](mailto:rajkumarn2002@gmail.com) |
| 🐙 **GitHub** | [github.com/Rajkumar2002-Rk](https://github.com/Rajkumar2002-Rk) |

---

<div align="center">
  <sub>Open to full-time roles · Available immediately · US (OPT/STEM OPT)</sub>
</div>
