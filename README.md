# 📧 Spam Email Detection using TensorFlow

## 📌 Overview
Spam messages are unsolicited or unwanted emails that flood users' inboxes. This project implements a deep learning-based spam email detector using **TensorFlow** and **Natural Language Processing (NLP)** techniques. The model classifies emails as either **Spam** or **Ham** (not spam) using a **Long Short-Term Memory (LSTM)** neural network.

## 🚀 Features
- **Exploratory Data Analysis (EDA)** to visualize spam and non-spam distributions
- **Text Preprocessing**: Stopword removal, punctuation removal, tokenization
- **Word2Vec Representation**: Convert text into numerical vectors
- **LSTM-based Deep Learning Model** for classification
- **Performance Evaluation** with accuracy and loss metrics

---

## 🛠 Installation & Setup
Ensure you have **Python 3.7+** installed, then install the required dependencies:

```bash
pip install numpy pandas matplotlib seaborn nltk wordcloud tensorflow scikit-learn
```

Clone the repository:
```bash
git clone https://github.com/yourusername/spam-email-detection.git
cd spam-email-detection
```
---

## 📂 Dataset
The dataset contains **5171 emails**, labeled as:
- **Spam (1)**: Unwanted, promotional, or phishing emails.
- **Ham (0)**: Legitimate, useful emails.
- 
📥 **Download Dataset**: [Emails.csv](https://www.kaggle.com/datasets/balaka18/email-spam-classification-dataset-csv)

---

## 🔧 Text Preprocessing
The preprocessing pipeline includes:
✅ **Removing Stopwords**
✅ **Removing Punctuation**
✅ **Word Tokenization & Vectorization**

---

## 🎯 Results
✅ **Test Accuracy:** 97.83%  
✅ **Loss:** 0.1088

---

