# AI-Powered Semantic Email Threat Analyzer

A Multi-Model Deep Learning Approach for Digital Forensics

## Overview

Email communication remains one of the most common vectors for cyber threats, including phishing, fraud, harassment, and suspicious activities. Traditional keyword-based filtering systems often struggle to understand the semantic meaning and contextual intent behind modern malicious emails.

This project presents an **AI-Powered Semantic Email Threat Analyzer** that leverages Deep Learning and Transformer-based Natural Language Processing (NLP) models to classify emails into four forensic categories:

* Fraudulent
* Suspicious
* Harassment
* Normal

The system integrates multiple AI models and provides real-time predictions through an interactive threat intelligence dashboard to assist digital forensic investigators and cybersecurity professionals in semantic email analysis.

---

## Methodology

### 1. Data Collection and Preparation

The dataset consists of forensic email records categorized into four classes:

* Normal
* Fraudulent
* Harassment
* Suspicious

Preprocessing steps included:

* Missing value removal
* Duplicate removal
* Text normalization
* Tokenization
* Label encoding

### 2. Exploratory Data Analysis (EDA)

EDA was performed to:

* Analyze class distributions
* Identify dataset imbalance
* Understand forensic data characteristics
* Evaluate preprocessing effectiveness

### 3. Model Development

Three Deep Learning architectures were implemented and evaluated:

#### DeBERTa-v3

* Transformer-based architecture
* Disentangled attention mechanism
* Strong semantic understanding

#### RoBERTa

* Transformer-based language model
* Context-aware email classification
* Fine-tuned for multiclass prediction

#### LSTM-GRU Hybrid

* Sequential deep learning architecture
* Captures contextual dependencies in email text
* Combines LSTM and GRU layers

### 4. Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

### 5. Threat Intelligence Dashboard

A real-time dashboard was developed to:

* Upload and analyze emails
* Display model predictions
* Show confidence scores
* Visualize probability distributions
* Support forensic investigation workflows

---

## Results

| Model      | Accuracy |
| ---------- | -------- |
| LSTM-GRU   | 92.76%   |
| RoBERTa    | 95.10%   |
| DeBERTa-v3 | 95.30%   |

### Key Findings

* Transformer-based models outperformed recurrent architectures.
* DeBERTa-v3 achieved the highest classification accuracy.
* RoBERTa demonstrated strong contextual understanding.
* LSTM-GRU provided effective sequential learning capabilities.
* Semantic analysis significantly improved forensic email triage and threat detection.

---

## Features

* Semantic Email Classification
* Fraud Detection
* Harassment Detection
* Suspicious Activity Identification
* Multi-Model AI Inference
* Interactive Threat Intelligence Dashboard
* Real-Time Prediction and Visualization
* Digital Forensics-Oriented Analysis

---

## Technologies Used

### Deep Learning & NLP

* DeBERTa-v3
* RoBERTa
* LSTM-GRU

### Programming Language

* Python

### Frameworks & Libraries

* PyTorch
* TensorFlow / Keras
* Hugging Face Transformers
* Scikit-learn
* Pandas
* NumPy

### Frontend & Dashboard

* React
* Vite
* FastAPI

---

## Conclusion

This project demonstrates the effectiveness of Deep Learning and Transformer-based NLP models for semantic email threat analysis in digital forensic investigations.

Experimental results indicate that transformer architectures, particularly DeBERTa-v3 and RoBERTa, provide superior contextual understanding and classification performance compared to traditional sequential models. The developed system successfully combines advanced AI models with an interactive threat intelligence dashboard, offering a practical solution for automated forensic triage and semantic threat detection.

---

Department of Cyber Security
Air University Islamabad
