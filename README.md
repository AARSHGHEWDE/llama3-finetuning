# 🦙 Fine-Tuning LLaMA 3 (8B) on Financial Text Data

This project focuses on **fine-tuning Meta’s LLaMA 3 8B** large language model on a custom financial dataset to tailor it for financial domain-specific language understanding and generation.

---

## 📌 Overview

Unlike basic prompt-based tasks with pre-trained models, this project performs **supervised fine-tuning (SFT)** to teach LLaMA-3 how to understand and respond to financial data more effectively. The dataset used (`alphads.csv`) consists of structured financial text suitable for downstream applications such as **financial Q&A**, **report generation**, or **market commentary synthesis**.

---

## 🧠 What's Included

- Preprocessing and formatting financial data for model ingestion  
- Tokenization and dataset structuring using Hugging Face Datasets  
- Model configuration and loading for LLaMA 3 8B  
- Training loop with evaluation metrics  
- Checkpoint saving and model deployment-ready structure  

---

## 🛠️ Technologies Used

- Python  
- Hugging Face Transformers & Datasets  
- PyTorch  
- LLaMA 3 8B (Meta)  
- GPU acceleration with bitsandbytes + deepspeed   
- Jupyter Notebook  
