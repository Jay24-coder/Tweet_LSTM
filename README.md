# Sentiment Analysis with LSTM

This repository contains a deep learning project focused on **Sentiment Analysis** using an **LSTM (Long Short-Term Memory)** neural network. The model is built using TensorFlow/Keras and trained on a dataset of labeled text samples.

## 📄 Project Overview

The goal of this project is to classify text data (e.g., tweets or user reviews) into sentiment categories such as **positive**, **neutral**, or **negative** using deep learning techniques.

### Features:
- Text cleaning and preprocessing
- Tokenization and padding
- Word embedding with Keras Embedding layer
- LSTM model for sequence classification
- Model evaluation and accuracy tracking

---

## 📁 Dataset

The dataset used is `Sentiment.csv`, which contains two main columns:
- `text`: The textual data (e.g., tweets)
- `sentiment`: Sentiment labels (e.g., positive, neutral, negative)

Make sure to place `Sentiment.csv` in the `data/` folder.

---

## 🔧 Dependencies

Install the required Python libraries:

```bash
pip install pandas numpy matplotlib nltk tensorflow scikit-learn
```

## 🔍 Data Preprocessing

Steps involved:

- Convert text to lowercase
- Remove "RT" (retweet) prefix
- Remove stopwords using NLTK
- Remove special characters
- Tokenize and pad sequences
- Encode sentiment labels

---

## 🧠 Model Architecture
The model architecture includes:
- Embedding layer: Converts words to dense vectors
- SpatialDropout1D: For regularization
- LSTM layer: Captures sequential dependencies
- Dense output layer: Classifies into sentiment categories

---

## 📬 Contact
For questions or feedback, feel free to open an issue or reach out.