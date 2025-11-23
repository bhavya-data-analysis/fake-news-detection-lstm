# 📰 Fake News Detection (NLP + Deep Learning)

<img src="assets/banner.png" width="100%">

This project detects **fake vs. real news** using NLP, Machine Learning, and Deep Learning models.  
The dataset used was **True.csv** and **Fake.csv**.

All work is implemented in ONE notebook:

---

## 🔍 Overview
The notebook includes:
- Data cleaning & preprocessing  
- TF-IDF text vectorization  
- Logistic Regression  
- Random Forest  
- LSTM model  
- CNN model  
- Confusion matrix, accuracy, recall, precision, F1  

---

## 🧠 Models Implemented

### **Logistic Regression**
- TF-IDF baseline  
- Accuracy: ~84%

### **Random Forest**
- Identifies top predictive words  
- Accuracy: ~85%

### **LSTM (Best Model)**
- Training Accuracy: ~93.7%  
- Validation Accuracy: ~90.8%  
- Best overall performance

### **CNN Model**
- Strong at extracting local text patterns  
- Accuracy: ~90%

---

## 📈 Results Summary

| Model | Accuracy |
|-------|----------|
| Logistic Regression | ~84% |
| Random Forest | ~85% |
| LSTM | **~92%** |
| CNN | ~90% |

---

## 📁 Project Structure

```

fake-news-detection-nlp/
│── data/ (empty)
│── notebooks/
│ └── Fake_news_detection.ipynb
│── assets/
│ └── banner.png
│── README.md

```

---

## 🛠 Tech Stack
- Python  
- TensorFlow / Keras  
- Scikit-Learn  
- Pandas / NumPy  
- NLP preprocessing  
- Matplotlib / Seaborn  

---

## 🚀 Future Work
- Add Transformer models (BERT/RoBERTa)  
- Deploy with Streamlit or Flask  
- Add multilingual support  

---

## 👤 Author
**Bhavya Pandya**

