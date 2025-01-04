# Fake News Detection Using Logistic Regression 📰🤖

This project focuses on detecting fake news using machine learning techniques, specifically **Logistic Regression** with TF-IDF features. The goal is to classify news articles as either **Fake** or **Real** based on their content.

---

## **Project Overview**
In this project:
- The dataset is processed and cleaned in a step-by-step manner within the Jupyter Notebook.
- **TF-IDF vectorization** is used to convert textual data into numerical features.
- A **Logistic Regression** model is trained and evaluated on the dataset.

---

## **Dataset**
The dataset used for this project can be downloaded from Kaggle:
- [Fake News Dataset](https://www.kaggle.com/c/fake-news/data)

### **Instructions**:
1. Download the dataset from the Kaggle link above.
2. Place the dataset files (e.g., `train.csv` and `test.csv`) in your working directory if you want to preprocess it from scratch.
3. Alternatively, run the Jupyter Notebook to see the preprocessing and modeling steps.

> Note: The dataset is **not included** in this repository due to size limitations.

---

## **Features**
- 🧹 **Text Preprocessing**:
  - Stopword removal and text cleaning are performed in the notebook.
  - Data is vectorized using **TF-IDF**.
- 🧠 **Machine Learning**:
  - A **Logistic Regression** model is trained to classify Fake vs. Real news.
- 📊 **Evaluation Metrics**:
  - Metrics include Accuracy, Precision, Recall, F1-score, and ROC-AUC.

---

## **Project Files**
This repository contains:
1. `FakeNews.ipynb`: The main Jupyter Notebook with the following steps:
   - Dataset preprocessing.
   - Feature extraction using TF-IDF.
   - Logistic Regression model training and evaluation.
2. Images of the results visulizations.

---

## **Results**
- **Accuracy**: 64% on the test set.
- **ROC-AUC**: 0.68
- **Confusion Matrix**:
  - Visualized in the notebook.
- **ROC Curve**:
  - Visualized in the notebook.
- **Metrics**:
  - Visualized in the notebook.

---

## **How to Run the Project**
### **Step 1: Clone the Repository**
Clone this repository to your local machine:
```bash
git clone https://github.com/your-username/fake-news-detection.git
cd fake-news-detection
```
### **Step 2: Download the Data**
- [Fake News Dataset](https://www.kaggle.com/c/fake-news/data)

### **Step 3: Run the Notebook**
[FakeNews.ipynb](notebook/FakeNews.ipynb)
