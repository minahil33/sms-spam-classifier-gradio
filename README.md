# SMS Spam Classifier

SMS Spam Classifier using NLP, TF-IDF, and Multinomial Naive Bayes with an interactive Gradio interface for real-time spam detection, demonstrating text preprocessing, machine learning, and model deployment in Python.

---

## 📌 Project Overview
* **Domain:** NLP / Text Classification
* **Problem Type:** Binary Classification (Ham / Spam)
* **Dataset Size:** 5,572 SMS messages
* **Hardware Requirements:** None (CPU only)
* **Target F1-Score (Spam):** 0.93 – 0.97

---

## 🛠️ Key Pipeline & Features
1. **Exploratory Data Analysis (EDA):** Class distribution inspection and lexical text structure analysis.
2. **Text Preprocessing:** Automated text normalization, noise cleaning, stop-word removal, and tokenization.
3. **Feature Extraction:** Vectorization using **Bag of Words (BoW)** and **TF-IDF** matrices.
4. **Model Training & Comparison:** Evaluating probabilistic classifiers including **Multinomial Naive Bayes**.
5. **Metric Evaluation & Error Analysis:** Beyond simple accuracy, focusing on **Precision**, **Recall**, and **F1-Score** to minimize false positives.
6. **Interactive Deployment:** Real-time message testing via a local **Gradio** web user interface.

---

## 🚀 Getting Started

### 1. Requirements
* Python 3.x
* `scikit-learn`
* `nltk`
* `pandas`
* `numpy`
* `gradio`
