# 📧 Spam Email Detector using Machine Learning

A Machine Learning project that classifies emails as **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) techniques. The project uses the **Kaggle Spam Email Dataset**, converts text into numerical features using **TF-IDF Vectorization**, and trains a **Multinomial Naïve Bayes** classifier for accurate spam detection.

---

## 🚀 Project Overview

Email spam detection is one of the most common applications of Natural Language Processing (NLP). This project builds an intelligent classifier capable of distinguishing spam emails from legitimate ones by analyzing the email text.

The workflow includes:

- Loading the Kaggle spam email dataset
- Cleaning and preprocessing email text
- Tokenization and stopword removal
- TF-IDF feature extraction
- Training a Multinomial Naïve Bayes classifier
- Evaluating model performance
- Predicting whether new emails are Spam or Ham

---

## ✨ Features

- 📂 Uses Kaggle Spam Email Dataset
- 🧹 Data Cleaning and Text Preprocessing
- 📝 Tokenization using NLTK
- 🔤 Stopword Removal
- 🔢 TF-IDF Vectorization
- 🤖 Multinomial Naïve Bayes Classifier
- 📊 Accuracy, Precision, Recall & F1-Score Evaluation
- 📧 Predict Spam/Ham for New Emails
- 📒 Implemented in Jupyter Notebook

---

## 📁 Dataset

The dataset contains labeled email messages categorized into:

- **Spam**
- **Ham (Not Spam)**

Source:
- Kaggle Spam Email Dataset

Typical dataset columns:

| Column | Description |
|---------|-------------|
| Category | Spam or Ham |
| Message | Email text |

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- TF-IDF Vectorizer
- Multinomial Naïve Bayes
- Jupyter Notebook

---

## 📚 Machine Learning Workflow

### 1. Data Collection
- Load spam email dataset from Kaggle.

### 2. Data Preprocessing
- Remove unnecessary characters
- Convert text to lowercase
- Remove punctuation
- Remove stopwords
- Tokenization

### 3. Feature Extraction
- Convert text into numerical vectors using TF-IDF.

### 4. Model Training
- Train the Multinomial Naïve Bayes classifier.

### 5. Model Evaluation
Evaluate the model using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

### 6. Prediction
Predict whether an unseen email is:

- 📧 Spam
- ✅ Ham

---

## 📂 Project Structure

```
Spam-Email-Detector/
│
├── SpamEmailDetector.ipynb
├── README.md
└── dataset.csv (optional)
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Spam-Email-Detector.git
```

Navigate to the project folder:

```bash
cd Spam-Email-Detector
```

Install dependencies:

```bash
pip install pandas numpy scikit-learn nltk
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
SpamEmailDetector.ipynb
```

---

## 📊 Model Used

**Multinomial Naïve Bayes**

This algorithm is widely used for text classification because it:

- Works efficiently with TF-IDF features
- Performs well on NLP tasks
- Fast training and prediction
- High accuracy for spam detection

---

## 📈 Evaluation Metrics

The model is evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

## 💡 Future Improvements

- Deploy using Flask or Streamlit
- Build a web interface
- Use deep learning models (LSTM/BERT)
- Add real-time email classification
- Improve preprocessing with stemming and lemmatization

---

## 🎯 Learning Outcomes

Through this project, I learned:

- Natural Language Processing (NLP)
- Text preprocessing
- TF-IDF Vectorization
- Naïve Bayes Classification
- Machine Learning model evaluation
- Scikit-learn workflow

