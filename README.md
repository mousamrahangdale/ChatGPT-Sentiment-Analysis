# 🚀 ChatGPT Sentiment Analysis

## 📌 Overview

This project implements a complete end-to-end Sentiment Analysis pipeline comparing Traditional Machine Learning and Transformer-based Deep Learning approaches.

The workflow includes:
- Data preprocessing & Exploratory Data Analysis (EDA)
- TF-IDF + Logistic Regression (optimized with Optuna)
- Handling class imbalance using SMOTE
- Fine-tuned DistilBERT model
- Model comparison & error analysis
- A/B Testing
- LLM-based sentiment experimentation

This notebook demonstrates real-world NLP system design and model benchmarking.

---

## 🧠 Project Pipeline

### 1️⃣ Data Processing & EDA
- Data loading
- Text cleaning & preprocessing
- Exploratory Data Analysis
- Class distribution visualization
- Graph plots & insights

---

### 2️⃣ Traditional ML Model

#### 🔹 Feature Engineering
- TF-IDF Vectorization

#### 🔹 Class Imbalance Handling
- SMOTE (Oversampling)

#### 🔹 Model
- Logistic Regression

#### 🔹 Hyperparameter Optimization
- Optuna tuning

#### 🔹 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Performance Visualization

---

### 3️⃣ Transformer Model

#### 🔹 Model Used
- Fine-tuned DistilBERT

#### 🔹 Process
- Tokenization using DistilBERT tokenizer
- Contextual Embeddings
- Model Fine-tuning
- Evaluation using same metrics for fair comparison

#### 🔹 Evaluation
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Performance Visualization

---

### 4️⃣ Model Comparison

- ML vs DistilBERT comparison
- Error Analysis
- Misclassification inspection
- Visualization-based performance comparison
- Statistical comparison

---

### 5️⃣ A/B Testing

- Performance benchmarking
- Statistical testing between both models
- Controlled evaluation framework

---

### 6️⃣ LLM Integration

- Sentiment prediction using LLM
- Comparison between:
  - Logistic Regression
  - DistilBERT
  - LLM
- Advanced NLP experimentation

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Optuna
- HuggingFace Transformers
- PyTorch / TensorFlow
- LLM API

---

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Error Analysis
- A/B Testing Results

---

## ▶️ How to Run

### 1️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 2️⃣ Run Notebook
```bash
jupyter notebook
```

Run all cells sequentially to reproduce the full ML → Transformer → Comparison → A/B → LLM pipeline.

---

## 📈 Key Learnings

- Impact of class imbalance in NLP models
- TF-IDF vs Transformer Embeddings comparison
- Hyperparameter tuning using Optuna
- Error analysis techniques
- Practical A/B testing for model comparison
- Real-world NLP system benchmarking

---

## 💼 Project Strength

This project demonstrates:

✔ Strong NLP fundamentals  
✔ Machine Learning optimization  
✔ Transformer fine-tuning  
✔ Model benchmarking strategy  
✔ Error analysis mindset  
✔ Experimental AI evaluation  

---

⭐ If you find this project useful, consider giving it a star!
