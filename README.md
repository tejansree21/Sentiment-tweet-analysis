# Sentiment Analysis on Tweets

### Overview
This project analyzes the **sentiment** (positive, negative, or neutral) of tweets using **Machine Learning** and **Natural Language Processing (NLP)**.  
It cleans tweet text, converts it into TF-IDF features, and uses a **Logistic Regression** model for classification.

---

### Algorithms Used
- Logistic Regression  
- TF-IDF Vectorization  
- Label Encoding  

---

### Dataset
You can use:
- [Sentiment140 Dataset (Kaggle)](https://www.kaggle.com/datasets/kazanova/sentiment140)
- Or your own custom dataset with columns:
  - `text` → tweet text  
  - `sentiment` → label (positive / negative / neutral)

---

### Dependencies
bash
pip install pandas numpy scikit-learn matplotlib seaborn joblib

predict_sentiment("I love using AI models for fun projects!") 
# Output: positive
