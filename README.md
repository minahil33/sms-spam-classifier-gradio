# SMS Spam Classifier

An end-to-end **SMS Spam Classifier** developed using **Machine Learning** and **Natural Language Processing (NLP)**. This project classifies SMS messages as **Spam** or **Ham** by applying text preprocessing, feature extraction, model training, evaluation, and deployment. Multiple vectorization techniques and machine learning algorithms are implemented and compared to identify the best-performing model. The project also includes an interactive **Gradio** web interface for real-time spam detection.

---

## Project Overview

| Attribute | Details |
|-----------|---------|
| Domain | Natural Language Processing (NLP) |
| Problem Type | Binary Text Classification |
| Classes | Ham / Spam |
| Dataset | SMS Spam Collection Dataset |
| Dataset Size | 5,572 SMS Messages |
| Hardware | CPU Only |
| Deployment | Gradio Web Interface |

---

## Features

- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Text normalization
- Tokenization
- Stop-word removal
- Stemming
- Feature extraction using:
  - Bag of Words (BoW)
  - TF-IDF
  - TF-IDF with Bigrams
- Training and comparison of multiple machine learning models
- Performance evaluation using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix
- Error analysis
- Interactive Gradio interface for real-time SMS classification

---

## Machine Learning Models

| Vectorizer | Algorithm |
|------------|-----------|
| Bag of Words (BoW) | Multinomial Naive Bayes |
| TF-IDF | Multinomial Naive Bayes |
| Bag of Words (BoW) | Complement Naive Bayes |
| TF-IDF | Logistic Regression |
| TF-IDF (Bigrams) | Multinomial Naive Bayes |

---

## Machine Learning Pipeline

1. Load the SMS Spam Collection dataset
2. Perform Exploratory Data Analysis (EDA)
3. Clean and preprocess text data
4. Convert text into numerical features using BoW and TF-IDF
5. Train multiple machine learning models
6. Compare model performance
7. Evaluate using classification metrics
8. Perform error analysis
9. Deploy the best-performing model with Gradio

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- Gradio
- Jupyter Notebook

---

## Installation

Clone the repository:

```bash
git clone https://github.com/minahil33/sms-spam-classifier-gradio.git
```

Navigate to the project directory:

```bash
cd sms-spam-classifier-gradio
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Run the Gradio application:

```bash
python app.py
```

---

## Project Structure

```text
sms-spam-classifier-gradio/
│
├── SMS_Spam_Classifier.ipynb
├── app.py
├── requirements.txt
├── README.md
├── dataset/
└── model/
```

---

## Learning Outcomes

This project demonstrates:

- Natural Language Processing (NLP)
- Text preprocessing and cleaning
- Feature engineering using Bag of Words and TF-IDF
- Binary text classification
- Comparison of multiple machine learning algorithms
- Model evaluation and performance analysis
- Error analysis for classification models
- Building an interactive web application using Gradio

---

## Future Improvements

- Deploy the application online using Hugging Face Spaces.
- Experiment with advanced NLP models and transformer-based architectures.
- Improve performance through hyperparameter tuning and feature engineering.

---

## License

Copyright © 2026 Minahil. All rights reserved.

This repository is shared for portfolio and educational viewing purposes only. Copying, modifying, or redistributing any part of this repository without prior written permission is prohibited.
