---
layout: page
title: Projects
---

## Fraud Detection System (Real-time ML Pipeline)

End-to-end production-style credit card fraud detection system built to handle extreme class imbalance (~0.17% fraud cases). Developed a scalable ML pipeline using XGBoost (CPU) with Spark/SQL preprocessing in Databricks, and trained/evaluated models on AWS EC2 (free tier). Implemented full MLOps workflow with versioned artifacts stored in S3 and deployed a serverless inference service using AWS Lambda (container image) and API Gateway. Exposed real-time predictions via a Streamlit dashboard for monitoring and evaluation. Achieved ROC-AUC 0.997, precision 0.89, recall 0.97 on held-out data.

**Tech:** Python, XGBoost, Spark/SQL, Databricks, AWS EC2, AWS Lambda, API Gateway, S3, Streamlit
**Links:**
<p>
  <strong>Links:</strong><br/>
  <a href="https://github.com/AKholman/Credit-card-fraud-detection-aws-pipeline" target="_blank">GitHub Repository</a><br/>
  <a href="https://fraud-detection-82yj5vkxtevasdsitmgjsm.streamlit.app/" target="_blank">Live Demo</a>
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