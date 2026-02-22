📌 Project Overview
This project implements a complete end-to-end Sentiment Analysis pipeline comparing traditional Machine Learning and Transformer-based Deep Learning approaches.
The workflow starts with data preprocessing and exploratory analysis, followed by a TF-IDF + Logistic Regression model optimized with Optuna and SMOTE. It then advances to fine-tuning a DistilBERT transformer model. Both models are evaluated, compared, and analyzed using statistical metrics, error comparison, A/B testing, and LLM-based experimentation.

🧠 Project Pipeline
1️⃣ Data Processing & EDA

Data loading

Text cleaning & preprocessing

Exploratory Data Analysis

Class distribution analysis

Graph & visualization plots

2️⃣ Traditional ML Model
🔹 Feature Engineering

TF-IDF Vectorization

🔹 Class Imbalance Handling

SMOTE oversampling

🔹 Model

Logistic Regression

🔹 Hyperparameter Optimization

Optuna for tuning

🔹 Evaluation Metrics

Accuracy

Precision

Recall

F1 Score

Confusion Matrix

Performance Visualizations

3️⃣ Transformer Model
🔹 Model Used

Fine-tuned DistilBERT

🔹 Process

Tokenization using transformer tokenizer

Contextual embeddings

Model fine-tuning

Evaluation using same metrics for fair comparison

🔹 Evaluation

Accuracy

Precision

Recall

F1 Score

Confusion Matrix

Performance Visualizations

4️⃣ Model Comparison

ML vs DistilBERT performance comparison

Error analysis

Misclassification inspection

Visualization-based comparison

Statistical comparison

5️⃣ A/B Testing

Comparative evaluation framework

Statistical comparison between both models

Performance benchmarking

6️⃣ LLM Integration

Testing sentiment output using LLM

Comparing traditional ML, Transformer, and LLM outputs

Advanced NLP experimentation

🛠️ Tech Stack

Python

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn

SMOTE (Imbalanced-learn)

Optuna

HuggingFace Transformers

PyTorch / TensorFlow

LLM integration

📊 Evaluation Metrics Used

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

Error Analysis

A/B Testing comparison

📈 Key Learnings

Impact of class imbalance on sentiment models

Performance difference between TF-IDF vs Transformer embeddings

Effect of hyperparameter tuning using Optuna

Practical model benchmarking techniques

Real-world error analysis strategies

Transformer superiority in contextual understanding

▶️ How to Run
Install Dependencies
pip install -r requirements.txt
Run Notebook
jupyter notebook
