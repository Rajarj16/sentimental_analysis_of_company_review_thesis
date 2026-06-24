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

1. What is the performance gap between the RoBERTa + Bi-LSTM ensemble and individual baseline models?
2. What is the contribution of domain-specific fine-tuning of RoBERTa to classification performance?
3. Which ensemble integration strategy — hard voting, soft voting, weighted averaging, or stacking — produces the highest Macro F1-Score?
4. How do sentiment classification patterns correlate with employer branding metrics such as star ratings?
5. Can a web-based multi-company employer sentiment comparison platform generate interpretable results for HR practitioners?
6. What linguistic features and thematic patterns characterise positive, neutral, and negative employer reviews?

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

## Models and Methods

### Base Models
- **RoBERTa-base** (Liu et al., 2019) — 124.6M parameters, domain fine-tuned in 2 stages
- **Bi-LSTM** (Hochreiter & Schmidhuber, 1997) — 5.85M parameters, GloVe-300 embeddings

### Ensemble Strategies
- Soft Voting (equal-weight probability averaging)
- Hard Voting (majority class voting)
- Weighted Averaging (w₁=0.6 RoBERTa, w₂=0.4 Bi-LSTM)
- Stacking with Logistic Regression meta-classifier (5-fold OOF)

### Explainability
- **SHAP** (SHapley Additive exPlanations) — token-level feature importance
- Dominant positive features: "great", "management", "pay"
- Dominant negative features: "terrible", "management", "return"

---
## Technologies

| Category | Tools |
|---|---|
| Language | Python 3 |
| Deep Learning | PyTorch, Hugging Face Transformers |
| Classical ML | Scikit-learn |
| NLP | NLTK, GloVe-300, SHAP |
| Data | Pandas, NumPy |
| Visualisation | Matplotlib, Seaborn |
| Web Prototype | HTML, CSS, JavaScript |
| Environment | Google Colab |

---

## Running the Project

### Open the Notebook in Google Colab

Upload `EmpulseAI_Thesis_Notebook_REAL_DATA.ipynb` and `glassdoor_sample_for_colab.csv` to Google Colab and run all cells sequentially.

### View the Web Prototype

Open `index.html` in any web browser, or visit the live demo:
https://employer-sentiment-thesis.netlify.app

Note: The prototype displays simulated demonstration metrics. Real experimental results are in the notebook.

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

