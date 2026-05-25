
# Amazon Fine Food Reviews Sentiment Analysis

## Project Overview
This project performs Sentiment Analysis on the Amazon Fine Food Reviews dataset using Natural Language Processing (NLP) and Machine Learning techniques. The goal is to classify customer reviews into Positive and Negative sentiments based on review text and ratings.

---

# Data Cleaning

The following preprocessing and cleaning steps were performed:

✔ Remove missing values  
✔ Clean text data  
✔ Remove stopwords  
✔ Lemmatization  
✔ Normalize text  

Additional preprocessing included:
- Removing punctuation
- Removing special characters
- Removing HTML tags
- Removing URLs
- Converting text to lowercase

---

# Exploratory Data Analysis (EDA)

The project includes detailed EDA techniques such as:

✔ Sentiment distribution analysis  
✔ Review length analysis  
✔ Word analysis  
✔ Interactive visualizations  

Visualizations were created using:
- Plotly
- Seaborn
- Matplotlib
- WordCloud

---

# Machine Learning Models

The following machine learning algorithms were implemented and compared:

✔ Logistic Regression  
✔ Naive Bayes  
✔ Support Vector Machine (SVM)  

---

# Model Evaluation

The models were evaluated using standard classification metrics:

✔ Accuracy  
✔ Precision  
✔ Recall  
✔ F1-score  
✔ Confusion Matrix  

---

# Dataset Information

Dataset Used: Amazon Fine Food Reviews Dataset

Important columns:
- Score
- Text

Sentiment labels were generated as:

| Score | Sentiment |
|---|---|
| 1–2 | Negative |
| 4–5 | Positive |
| 3 | Neutral (removed) |

---

# NLP Techniques Used

- Text preprocessing
- Stopword removal
- Lemmatization
- TF-IDF Vectorization

---

# Best Performing Model

The SVM model achieved the best overall performance due to its effectiveness with high-dimensional sparse text data.

Expected accuracy:
- Logistic Regression: 90–94%
- Naive Bayes: 86–90%
- SVM: 92–95%

---

# Project Workflow

```text
Dataset
   ↓
Data Cleaning
   ↓
EDA
   ↓
Sentiment Label Creation
   ↓
Text Preprocessing
   ↓
TF-IDF Vectorization
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Prediction System
```

---

# Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Plotly
- Seaborn
- Matplotlib
- WordCloud
- Jupyter Notebook

---

# Conclusion

This project demonstrates how NLP and Machine Learning techniques can effectively classify customer reviews into sentiments. The combination of TF-IDF and SVM produced high classification performance and meaningful customer insight analysis.
