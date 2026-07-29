---
layout: page
title: Projects
---

## Fraud Detection System (Real-time ML Pipeline)

End-to-end production-style credit card fraud detection platform designed to handle extreme class imbalance (~0.17% fraud cases). Built a complete ML workflow using Databricks (Spark/SQL) for preprocessing, XGBoost (CPU) model training on AWS EC2, and AWS S3 for model artifact management. Achieved ROC-AUC 0.997, precision 0.89, and recall 0.97 on held-out data.

Implemented two production inference architectures:

Serverless AWS deployment: Containerized XGBoost inference service using AWS Lambda (container image) + API Gateway, with a Streamlit dashboard for real-time fraud prediction.
Kubernetes deployment: Dockerized FastAPI inference service deployed on Kubernetes, exposed through Kubernetes Service, with a separate Streamlit UI for interactive prediction.

Demonstrates end-to-end MLOps practices including model training, artifact management, containerization, cloud deployment, API development, and scalable model serving..

**Tech:** Python, XGBoost, Spark, SQL, Databricks, AWS EC2, AWS S3, AWS Lambda, API Gateway, Docker, Kubernetes, FastAPI, Streamlit
<p>
  <strong>Links:</strong><br/>
  <a href="https://github.com/AKholman/Credit-card-fraud-detection-aws-pipeline" target="_blank">GitHub Repository (AWS Lambda Version)</a><br/>
  <a href="https://fraud-detection-82yj5vkxtevasdsitmgjsm.streamlit.app/" target="_blank">Live Demo (AWS Lambda Version)</a><br/>
  <a href="https://github.com/AKholman/Fraud-Detection-XGBoost-FastAPI-Kubernetes" target="_blank">GitHub Repository (Kubernetes Version)</a><br/>
  <a href="https://fraud-detection-xgboost-fastapi-kubernetes-nkehcys9g2xcmyxzbrt.streamlit.app/" target="_blank">Live Demo (Kubernetes Version)</a>

</p>

---

## Production RAG System with Cloud Observability & Cost-Aware Serving

End-to-end production-grade Retrieval-Augmented Generation system with a decoupled cloud architecture. Built a FAISS-based retrieval pipeline using sentence-transformers (MiniLM) and served generation via Groq-hosted LLaMA-3.1-8B. Implemented a Colab → AWS workflow with versioned artifacts in S3 and a FastAPI inference layer on EC2. Added CloudWatch-based observability with structured logging, latency breakdown (embedding / FAISS / LLM), token usage tracking, and p95 latency analysis. Validated system stability with 60+ request tests and production-style monitoring.

Tech: Python, Sentence-Transformers, FAISS, FastAPI, AWS EC2, S3, CloudWatch, Groq LLM
Links:

<p> 
  <strong>Links:</strong><br/> 
  <a href="https://github.com/AKholman/RAG-System-with-Cloud-Observability-Cost-Aware-Serving" target="_blank">GitHub Repository</a><br/> 
</p>

---

## LLM Fine-Tuning (Mistral-7B + LoRA)
Built an instruction-tuning pipeline using LoRA/PEFT on Mistral-7B. Trained on Amazon reviews, synthetic Q&A, and product metadata using Google Colab (T4 GPU). Deployed quantized inference (QLoRA) via FastAPI.

**Tech:** PyTorch, PEFT, LoRA, QLoRA, FastAPI  
**Links:**  
<p>
  <strong>Links:</strong><br/>
  <a href="https://github.com/AKholman/ecommerce-llm-finetune-llm" target="_blank">GitHub Repository</a><br/>
</p>

---

## Stock Price Forecasting (LSTM)
End-to-end time-series ML system using PyTorch LSTM with Airflow orchestration, MLflow tracking, and Evidently monitoring. Achieved **1.64% MAPE**, outperforming all baselines.

**Tech:** PyTorch, Airflow, MLflow, Evidently, Streamlit  
**Links:**  
<p>
  <strong>Links:</strong><br/>
  <a href="https://github.com/AKholman/Deep-Learning-stock-forecasting-app" target="_blank">GitHub Repository</a><br/>
  <a href="https://akholman-deep-learning-stock-forecasting-app-app-uq0keh.streamlit.app/" target="_blank">Live Demo</a>
</p>

---

<p style="margin-top:40px; font-size:16px;">
  👉 For additional projects and experiments, see my
  <a href="https://github.com/AKholman" target="_blank">GitHub profile</a>.
</p>

---
## End-to-End RAG System
Production-ready Retrieval-Augmented Generation system using LangChain and Hugging Face embeddings, with ChromaDB vector search and FastAPI backend. Deployed via Docker with automated GitHub Actions CI/CD.

**Tech:** Python, LangChain, Hugging Face, ChromaDB, FastAPI, Docker  
**Links:**  
<p>
  <strong>Links:</strong><br/>
  <a href="https://github.com/AKholman/rag-langchain-ml-assistant" target="_blank">GitHub Repository</a><br/>
  <a href="https://huggingface.co" target="_blank">Live Demo</a>
</p>
---