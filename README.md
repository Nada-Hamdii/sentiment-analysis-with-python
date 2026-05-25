# Sentiment Analysis Project (NLP + Machine Learning)

## 📌 Overview

This project is a **Sentiment Analysis system** built using Python and Machine Learning techniques.  
It classifies text data (such as reviews or comments) into sentiment categories using Natural Language Processing (NLP).

The model is trained using a **Naive Bayes classifier** and evaluated with standard performance metrics.

---

## 📂 Dataset

The dataset used in this project is stored in:
dataset.csv

It contains text data and corresponding sentiment labels.

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- WordCloud
- Scikit-learn

---

## 🧠 Machine Learning Pipeline

1. Load and explore dataset using Pandas
2. Data cleaning and preprocessing
3. Text vectorization using **CountVectorizer**
4. Split dataset into training and testing sets
5. Train model using **Multinomial Naive Bayes**
6. Evaluate model using:
   - Accuracy Score
   - Classification Report
   - Confusion Matrix
7. Data visualization using Seaborn & Matplotlib
8. WordCloud visualization for most frequent words

---

## 📊 Model Used

- **Multinomial Naive Bayes**
A simple and efficient algorithm for text classification tasks.

---

## 📈 Evaluation Metrics

- Accuracy Score
- Precision / Recall / F1-score
- Confusion Matrix

---

## 📷 Visualizations

- Sentiment distribution plots
- Confusion matrix heatmap
- WordCloud of frequent words

---

## 🚀 How to Run the Project

##1. Clone the repository:

```bash
git clone https://github.com/your-username/sentiment-analysis-naive-bayes.git

##2. Install dependencies:

pip install pandas numpy seaborn matplotlib scikit-learn wordcloud

##3. Open the notebook:
jupyter notebook analyse de sentiments.ipynb

🎯 Goal of the Project

To build a simple but effective NLP model that can automatically detect sentiment from text data.