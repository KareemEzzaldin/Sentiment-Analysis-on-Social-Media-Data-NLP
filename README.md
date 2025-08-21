# Sentiment-Analysis-on-Social-Media-Data-NLP

## Overview
This project performs **sentiment analysis** on text data collected from **Reddit** and **Twitter**.  
It explores how opinions vary across platforms and compares the performance of **classical machine learning models** and **deep learning models**.

---

##  Data Overview
- **Reddit**  
  - 37,249 comments  
  - Labels: `-1` Negative, `0` Neutral, `1` Positive  
- **Twitter**  
  - 162,980 tweets  
  - Labels: `-1` Negative, `0` Neutral, `1` Positive  

Both datasets are **pre-cleaned** to remove noise and inconsistencies.

---

## 🛠 Project Workflow
- Data validation and preprocessing  
- Text cleaning and tokenization  
- Feature extraction using **TF-IDF** and **word embeddings**  
- Training **machine learning models** (Logistic Regression, SVM, etc.)  
- Training **deep learning models** (LSTM, GRU, etc.)  
- Model evaluation with accuracy, precision, recall, and F1-score  
- Visualization of sentiment distributions and model performance  

---

##  Key Insights
- Twitter data showed higher polarity due to short-form, opinion-driven text  
- Reddit comments provided richer context but required more processing  
- Embedding-based models outperformed TF-IDF in accuracy and generalization  
- Neural networks captured subtle sentiment patterns better than classical models  

---

## ⚙Tools and Technologies
- Python  
- Pandas, NumPy  
- NLTK, spaCy  
- Scikit-learn  
- TensorFlow, Keras  
- Matplotlib, Seaborn  

---

## 📈 Results
- Deep learning models achieved higher accuracy and generalization compared to classical models  
- Visual analysis showed strong patterns in polarity across both platforms  

---

## 🚀 How to Run

### Clone the repository
```bash
git clone https://github.com/KareemEzzaldin/Sentiment-Analysis-on-Social-Media-Data-NLP.git
cd Sentiment-Analysis-on-Social-Media-Data-NLP
