# 📝 Multi-Class Sentiment Analysis using Classical Machine Learning

A comprehensive Natural Language Processing (NLP) project that performs **multi-class sentiment analysis** by comparing multiple text vectorization techniques and machine learning algorithms.

---

# 📌 Project Overview

This project focuses on classifying text into **6 different sentiment classes** using classical NLP techniques. The objective was not only to build a sentiment classifier but also to compare different feature extraction methods and machine learning models to determine the best-performing pipeline.

---

# 🚀 Features

- Text preprocessing
- Bag of Words (BoW)
- TF-IDF Vectorization
- Multiple ML models
- Performance comparison
- Confusion Matrix
- Classification Report
- Accuracy comparison

---

# 📂 Dataset

The dataset contains text samples belonging to **6 sentiment classes**.

Example workflow:


Raw Text
      ↓
Text Cleaning
      ↓
Feature Extraction
      ↓
Machine Learning Model
      ↓
Prediction


---

# 🛠 Text Preprocessing

The following preprocessing steps were performed:

- Convert text to lowercase
- Remove punctuation
- Remove special characters
- Remove numbers
- Remove stopwords
- Tokenization
- Text normalization

---

# 📊 Feature Extraction Techniques

## 1. Bag of Words (BoW)

Converts text into numerical vectors based on word frequencies.

## 2. TF-IDF

Calculates the importance of each word based on its frequency within a document and across the corpus.

---

# 🤖 Machine Learning Models Used

- Multinomial Naive Bayes
- Logistic Regression
- Linear Support Vector Classifier (Linear SVC)
- SGD Classifier

---

# 📈 Model Comparison

| Vectorizer | Model | Accuracy |
|------------|--------|---------:|
| TF-IDF | Naive Bayes | **66.09%** |
| BoW | Naive Bayes | **76.81%** |
| TF-IDF | Logistic Regression | **86.28%** |
| BoW | Logistic Regression | **88.97%** |
| TF-IDF | Linear SVC | **89.19%** |
| BoW | Linear SVC | **89.03%** |
| TF-IDF | SGD Classifier | **89.19%** |
| 🏆 BoW | SGD Classifier | **89.66%** |

---

## 🏆 Best Performing Model

**Vectorizer:** Bag of Words

**Model:** SGD Classifier

*Accuracy:** **89.66%**

### Classification Report


Accuracy: 89.66%

Weighted Precision : 0.90
Weighted Recall    : 0.90
Weighted F1 Score  : 0.90

---

# 📊 Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK

---

# 📁 Project Structure


Sentiment-Analysis/
│
├── dataset/
├── notebooks/
├── models/
├── README.md
├── requirements.txt
└── sentiment_analysis.ipynb


---

# 📌 Workflow

Dataset
   │
   ▼
Data Cleaning
   │
   ▼
Text Preprocessing
   │
   ▼
BoW / TF-IDF
   │
   ▼
Model Training
   │
   ▼
Evaluation
   │
   ▼
Model Comparison


---

# 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

# 💡 Key Learnings

- Compared Bag of Words and TF-IDF representations.
- Evaluated multiple classical machine learning algorithms.
- Understood the impact of feature engineering on NLP tasks.
- Learned that the best vectorization technique depends on the dataset.
- Built a complete end-to-end NLP classification pipeline.

---

# 🔮 Future Improvements

- Word Embeddings (Word2Vec, GloVe, FastText)
- LSTM-based Sentiment Analysis
- GRU-based Sentiment Analysis
- Attention Mechanism
- Transformer-based Models (BERT)
- Streamlit Web Application Deployment

---

# 👨‍💻 Author

**Shaurya Kumar**

AI & Machine Learning Enthusiast

---

⭐ If you found this project useful, consider giving it a star!
