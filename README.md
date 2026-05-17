# 🚀 End-to-End Machine Learning Pipeline: Sentiment Analysis

## 📌 Project Overview
This repository contains my final project for the **[Codveda Technologies]** Machine Learning Internship. The objective of this project was to build a comprehensive machine learning pipeline, progressing from basic data preprocessing to advanced deep learning architectures. 

The project focuses on **Natural Language Processing (NLP)**, specifically performing sentiment analysis on a complex dataset of social media posts, categorizing over 190 unique emotions into structural sentiments.

---

## 🛠️ Technologies Used
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (Linear Regression, Logistic Regression, Decision Trees, Random Forest, SVM)
* **NLP Techniques:** TF-IDF (Term Frequency-Inverse Document Frequency)
* **Environment:** Jupyter Notebook

---

## 📂 Project Structure & Progression

This project is divided into three distinct difficulty levels, showcasing a clear progression of technical skills:

### 🔹 Level 1: Foundation & Basic Modeling
* **Data Preprocessing:** Cleaned the raw text data and implemented a custom data consolidation function to group 191 fragmented emotions into three core classes: `Positive`, `Negative`, and `Neutral`.
* **Feature Engineering:** Deployed a **TF-IDF Vectorizer** (1000 features) to translate textual data into numerical arrays for algorithmic processing.
* **Regression Analysis:** Built a Simple Linear Regression model to analyze continuous variables, predicting user 'Likes' based on 'Retweets'.

### 🔹 Level 2: Intermediate Techniques & Interpretability
* **Binary Classification:** Strategically filtered the dataset to isolate strictly 'Positive' and 'Negative' sentiments.
* **Probabilistic Modeling:** Deployed a **Logistic Regression** model on the binary subset to predict probabilistic outcomes.
* **Algorithmic Interpretability:** Engineered a **Decision Tree Classifier**, carefully tuning the `max_depth` hyperparameter to prevent overfitting while providing a clear, logical mapping of how the model classifies sentiment.

### 🔹 Level 3: Advanced Algorithms & Deep Learning
* **Ensemble Learning:** Constructed a **Random Forest Classifier** composed of 100 decision trees to boost predictive robustness and eliminate variance.
* **Margin-Based Classifiers:** Trained **Support Vector Machines (SVM)** using linear kernels to map high-dimensional mathematical boundaries between text classifications.

---

## 📊 Results & Performance
By applying data consolidation (grouping micro-emotions into macro-sentiments) and optimizing hyperparameters, the models achieved the following performances:
* **Linear Regression (Binary):** [1.00] Accuracy
* **Decision Tree:** [60]% Accuracy
* **Random Forest:** [71]% Accuracy
* **SVM:** [73]% Accuracy

*(Note: Exact accuracy metrics reflect the specific testing subset during the final run).*

---

## 💻 How to Run the Project
1. Clone this repository:
   ```bash
