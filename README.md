# sentiment-analysis
This project implements a simple sentiment analysis pipeline using the **Bag of Words (BoW)** technique for text vectorization and a **Naive Bayes** classifier for prediction.  
The goal is to classify text (e.g., reviews or comments) as **positive** or **negative**.

---

## 📌 Overview

Sentiment analysis is a Natural Language Processing (NLP) task that determines whether a piece of text expresses a positive or negative opinion.  
In this project:

- Text is converted into numerical features using **Bag of Words**
- A **Naive Bayes** model is trained on these features
- The model predicts sentiment on unseen text

This is a baseline ML approach (no deep learning).

---

## 🧠 Approach

1. **Preprocessing**
   - Lowercasing  
   - Removing punctuation  
   - Tokenization  
   - (Optional) Stopword removal  

2. **Feature Extraction**
   - Convert text into vectors using **Bag of Words (CountVectorizer)**

3. **Model**
   - Train a **Naive Bayes** classifier (MultinomialNB)

4. **Evaluation**
   - Accuracy  
   - Precision / Recall / F1-score  
   - Confusion matrix  

---
