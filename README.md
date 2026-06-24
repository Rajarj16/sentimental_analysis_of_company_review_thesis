# 💼 EmpulseAI: Multi-Class Sentiment Analysis of Company Reviews Using Ensemble Deep Learning Models

### Master's Thesis Project

---

## 📌 Project Overview

This repository contains the implementation, experiments, and prototype application developed as part of the Master's thesis:

**"Multi-Class Sentiment Analysis of Company Reviews Using Ensemble Deep Learning Models for Employer Branding."**

The study investigates how Natural Language Processing (NLP) and Deep Learning techniques can be used to analyse employee reviews and support employer branding insights.

The research evaluates individual and ensemble deep learning models for classifying employee reviews into:

* Positive
* Neutral
* Negative

The project also includes a lightweight prototype application (**EmpulseAI**) for comparative company sentiment analysis and visualisation.

---

## 🎯 Research Objectives

The objectives of this study are:

* To analyse employee review sentiment using NLP techniques
* To develop and evaluate RoBERTa and Bi-LSTM sentiment classification models
* To compare multiple ensemble learning strategies
* To evaluate model performance using standard classification metrics
* To develop a web-based prototype for company sentiment comparison and employer branding analysis

---

## 🧠 Deep Learning Models

The following models were implemented and evaluated:

### Individual Models

* RoBERTa (Transformer-based Language Model)
* Bi-LSTM (Bidirectional Long Short-Term Memory Network)

### Ensemble Strategies

* Hard Voting
* Soft Voting
* Weighted Averaging
* Stacking (Logistic Regression Meta-Learner)

---

## ⚙️ Methodology

The project follows the following workflow:

### Data Preprocessing

* Text cleaning
* Lowercasing
* Tokenization
* Sequence normalization
* Label preparation
* Dataset splitting (Training / Validation / Testing)

### Model Training

* Fine-tuning RoBERTa
* Training Bi-LSTM model
* Ensemble integration
* Hyperparameter tuning

### Evaluation Metrics

Models are evaluated using:

* Accuracy
* Precision
* Recall
* Macro F1-Score
* Confusion Matrix

---

## 📊 Key Research Questions

The study investigates:

1. Can ensemble deep learning models outperform individual models for employee review sentiment classification?

2. How effectively can RoBERTa be fine-tuned for employer-review sentiment analysis?

3. Which ensemble strategy performs best for multi-class sentiment classification?

4. How can sentiment analysis support employer branding and organisational reputation management?

5. Can a web-based sentiment comparison platform provide meaningful employer insights?

---

## 🗂️ Repository Structure

```text
├── EmpulseAI_Thesis_Notebook_REAL_DATA.ipynb
│   └── Final machine learning experiments and evaluation
│
├── Glassdoor_Dataset.csv
│   └── Dataset used in the study
│
├── index.html
│   └── EmpulseAI web application prototype
│
├── README.md
│   └── Project documentation
```

---

## 📂 Dataset Information

**Dataset Source:** Kaggle

**Dataset Type:** Employee Review Dataset

The dataset contains employee review text, company ratings, and sentiment-related information used for multi-class sentiment classification and employer branding analysis.

---

## 🛠️ Technologies Used

### Programming Language

* Python

### Machine Learning & NLP

* Transformers
* PyTorch
* Scikit-learn
* NLTK

### Data Analysis

* Pandas
* NumPy

### Visualisation

* Matplotlib
* Seaborn

### Web Application

* HTML
* CSS
* JavaScript

---

## ▶️ Running the Project

### Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/EmpulseAI.git
cd EmpulseAI
```

### Open Notebook

```bash
jupyter notebook EmpulseAI_Thesis_Notebook_REAL_DATA.ipynb
```

### Launch Web Application

Open:

```text
index.html
```

in your web browser.

---

## 🚀 Future Enhancements

Potential future improvements include:

* Larger-scale employer review datasets
* Additional transformer architectures
* Explainable AI (XAI) integration
* Real-time review analytics
* Live company sentiment tracking
* Advanced recommendation systems

---

## 👤 Authors

**Raja Ramaraj**

**Santhosh Selvan**

Master’s Thesis MSc Data Science and AI, Digital Analytics

