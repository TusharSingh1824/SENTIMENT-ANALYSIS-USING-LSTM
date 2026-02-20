# 📊 Sentiment Analysis using LSTM

## 🚀 Overview
This project implements a Deep Learning-based Sentiment Analysis model using LSTM (Long Short-Term Memory) architecture. The model classifies IMDB movie reviews as positive or negative by learning contextual patterns in sequential text data.

The project demonstrates a complete NLP pipeline including preprocessing, embedding, model training, and evaluation.

---
## ▶️ Run on Google Colab
---

## 📂 Dataset

Dataset used: **IMDB Dataset of 50K Movie Reviews**

Kaggle Link:  
https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

You can use either of the following methods inside Google Colab:

---

## 🔹 Option 1: Upload Dataset Manually (Easiest in Colab)

1. Download dataset from Kaggle link.
2. Open the notebook in Google Colab.
3. Upload CSV file using:

```python
from google.colab import files
uploaded = files.upload()
```

4. Load dataset normally using pandas.

---

## 🔹 Option 2: Use Kaggle API in Google Colab

1. Download `kaggle.json` from Kaggle → Account Settings.
2. In Colab, upload it:

```python
from google.colab import files
files.upload()
```

3. Configure Kaggle API:

```python
!mkdir -p ~/.kaggle
!cp kaggle.json ~/.kaggle/
!chmod 600 ~/.kaggle/kaggle.json
```

4. Install Kaggle CLI and download dataset:

```python
!pip install kaggle
!kaggle datasets download -d lakshmi25npathi/imdb-dataset-of-50k-movie-reviews
```

---

## 🧠 Model Architecture

- Embedding Layer  
- LSTM Layer  
- Dropout Regularization  
- Dense Output Layer (Sigmoid Activation)  

LSTM processes sequences as:

hₜ = LSTM(xₜ, hₜ₋₁)

This enables contextual understanding and captures long-term dependencies in text.

---

## 🛠️ Tech Stack

- Python  
- TensorFlow / Keras  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib  

---

## 🔄 Workflow

1. Text Cleaning & Preprocessing  
2. Tokenization & Sequence Padding  
3. Embedding Representation  
4. LSTM Model Training  
5. Evaluation (Accuracy, Precision, Recall, F1-Score)

---

## 📈 Results

- Achieved **88% validation accuracy**
- Improved generalization using Dropout
- Demonstrated contextual learning over traditional ML baseline

## 💼 Applications

- Customer review sentiment analysis  
- Social media monitoring  
- Financial news sentiment scoring  
- Risk signal extraction in fintech  

---

## 🤝 Connect

LinkedIn: https://linkedin.com/in/tushar-singh-022605244  
GitHub: https://github.com/TusharSingh1824  

⭐ If you found this useful, consider giving it a star!
