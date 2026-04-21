# Linguistic Analysis of Bias and Emotion in Indian Health News

Selected for presentation at ICAART Conference

A scalable NLP pipeline for detecting media bias, emotional framing, and potential misinformation in Indian health news articles using transformer-based deep learning models.

---

## Table of Contents
- Overview  
- Features  
- Dataset  
- Methodology  
- Installation  
- Usage  
- Results  
- Project Structure  
- Technologies Used  
- Key Learnings  

---

##  Overview

With the rapid growth of digital media, news platforms have become a major source of health-related information. However, biased reporting and emotionally charged content can significantly influence public perception.

This project analyzes linguistic patterns in Indian health news articles to detect:
- Emotional framing  
- Media bias  
- Potential misinformation  

The pipeline is designed to handle large-scale unstructured text data (50,000+ articles) and extract meaningful insights using modern NLP techniques.

---

## Features

- Large-scale NLP pipeline for 50K+ articles  
- Transformer-based models (RoBERTa, DistilBERT)  
- Emotion classification (anger, joy, optimism, sadness)  
- Bias detection through linguistic and contextual patterns  
- Topic modeling using BERTopic  
- Interpretable outputs and thematic insights  

---

## Dataset

Due to size constraints, the full dataset is not included in this repository.

Dataset Link:  
https://drive.google.com/drive/folders/1GT5QRZrNAMNFMKV9u3zrlRoVMwQvPeu7?usp=drive_link

Dataset Details:
- Size: 50,000+ health news articles  
- Sources: Major Indian news platforms  
- Features: Title, content, source, metadata  
- Type: Unstructured textual data  

---

## Methodology

### 1. Data Preprocessing
- Text cleaning and normalization  
- Noise removal and tokenization  
- Preparation for transformer-based models  

### 2. Emotion Classification (DistilBERT)
- Fine-tuned model for emotion detection  
- Classes: anger, joy, optimism, sadness  
- Captures contextual emotional tone  

### 3. Bias Detection (RoBERTa)
- Identifies framing bias and linguistic patterns  
- Detects emotionally loaded or misleading content  

### 4. Topic Modeling (BERTopic)
- Uses transformer embeddings for clustering  
- Identifies dominant themes in health reporting  

### 5. Evaluation
- Metrics: Accuracy, F1-score  
- Focus on class imbalance and model optimization  

---

## Installation

### Prerequisites
- Python 3.8+  

### Setup
```bash
git clone https://github.com/your-username/bias-emotion-health-news-nlp.git
cd bias-emotion-health-news-nlp
pip install -r requirements.txt
```

##  Usage

Run the notebook:

```bash
jupyter notebook
```

## Workflow

- Data preprocessing  
- Model training and fine-tuning  
- Topic modeling  
- Evaluation and analysis  

---

## Results

- **Accuracy:** 86.3%  
- **F1 Score:** 0.74  

### Key Insights

- Emotionally intense articles tend to show higher bias
- Transformer models outperform traditional ML approaches
- Topic modeling reveals underlying themes in reporting
---

## Technologies Used

- Python  
- Pandas, NumPy  
- Scikit-learn  
- HuggingFace Transformers  
- BERTopic  
- NLTK  
- Matplotlib, Seaborn  

---

## Key Learnings

- Importance of clean and well-structured text data  
- Effectiveness of transformer models for NLP tasks  
- Handling class imbalance in real-world datasets  
- Combining supervised and unsupervised techniques improves insights  
- Building scalable pipelines for large datasets  

---

## Note

This repository contains a lightweight version of the project.  
The full dataset is available via the link above due to size constraints.

---

