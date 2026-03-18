Linguistic Analysis of Bias and Emotion in Indian Health News
A scalable NLP pipeline for detecting media bias, emotional framing, and potential misinformation in Indian health news articles using transformer-based deep learning models.

📋 Table of Contents
Overview
Features
Dataset
Methodology
Installation
Usage
Results
Project Structure
Technologies Used
Key Learnings

🎯 Overview
With the rapid growth of digital media, news platforms have become a major source of health-related information. However, the presence of biased reporting and emotionally charged content can significantly influence public perception.
This project focuses on analyzing linguistic patterns in Indian health news articles to detect:
Emotional framing
Media bias
Potential misinformation signals
The pipeline is designed to handle large-scale unstructured text data (50,000+ articles) and extract meaningful insights using modern NLP techniques.
This work has also been selected for presentation at the ICAART conference, highlighting its research and practical relevance.

✨ Features
📊 Large-scale NLP pipeline for 50K+ articles
🤖 Transformer-based models (RoBERTa, DistilBERT)
🧠 Emotion classification (anger, joy, optimism, sadness)
⚖️ Bias detection through linguistic and contextual patterns
🔍 Topic modeling using BERTopic
📈 Interpretable outputs and thematic insights

📊 Dataset
Due to size constraints, the full dataset is not included in this repository.

👉 Access Dataset Here:
Google Drive Link : https://drive.google.com/drive/folders/1GT5QRZrNAMNFMKV9u3zrlRoVMwQvPeu7?usp=drive_link

Dataset Details:
Size: 50,000+ health news articles
Sources: Major Indian news platforms
Features: Title, content, source, metadata
Type: Unstructured textual data

🔬 Methodology
1. Data Preprocessing
Text cleaning and normalization
Removal of noise and irrelevant tokens
Tokenization and preparation for transformer models
2. Emotion Classification (DistilBERT)
Fine-tuned transformer model for emotion detection
Classes: anger, joy, optimism, sadness
Captures contextual emotional tone in articles
3. Bias Detection (RoBERTa)
Identifies framing bias and linguistic patterns
Detects emotionally loaded and potentially misleading content
Analyzes subtle differences in narrative tone
4. Topic Modeling (BERTopic)
Uses transformer embeddings for semantic clustering
Identifies dominant themes in health reporting
Improves interpretability of large text corpora
5. Evaluation & Optimization
Metrics: Accuracy, F1-score
Focus on handling class imbalance
Model fine-tuning for improved generalization

🚀 Installation
Prerequisites
Python 3.8+
Recommended: GPU for faster training
Setup
git clone https://github.com/your-username/bias-emotion-health-news-nlp.git
cd bias-emotion-health-news-nlp
pip install -r requirements.txt
💻 Usage
Run the main notebook:
jupyter notebook
Suggested workflow:
Data preprocessing
Model training (DistilBERT / RoBERTa)
Topic modeling (BERTopic)
Evaluation and analysis

📈 Results
Accuracy: 86.3%
F1 Score: 0.74
Key Insights:
Emotionally intense articles are more likely to exhibit bias
Transformer models significantly outperform traditional ML methods
Topic modeling helps uncover hidden thematic patterns in news reporting

📁 Project Structure
bias-emotion-health-news-nlp/
│── README.md
│── requirements.txt
│── main_notebook.ipynb
│── data_sample.csv
│── outputs/
│   ├── topic_results.csv
│   ├── emotion_predictions.csv
│── models/
│── utils/

🛠 Technologies Used
Core
Python
Pandas, NumPy
Scikit-learn
NLP & Deep Learning
HuggingFace Transformers (RoBERTa, DistilBERT)
BERTopic
NLTK
Visualization
Matplotlib
Seaborn

💡 Key Learnings
Data quality and preprocessing are critical in NLP pipelines
Transformer models are highly effective for contextual understanding
Handling class imbalance is essential for reliable evaluation
Combining supervised and unsupervised methods improves interpretability
Building scalable pipelines is key for real-world applications

📌 Note
This repository contains a lightweight version of the project.
The full dataset is available via the link above due to size constraints.
