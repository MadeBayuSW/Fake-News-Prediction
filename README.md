# 📰 Fake News Detection with Machine Learning  

## 📌 Project Overview  
This project focuses on detecting **Fake News vs True News** using **Natural Language Processing (NLP)** and **Machine Learning** techniques.  
The goal is to build a reliable classification model that can identify misleading information in online news articles.  

---

## 🔧 Tools & Libraries  
- Python (Pandas, NumPy, Scikit-learn, NLTK)  
- Matplotlib & Seaborn (visualization)  
- Jupyter Notebook / Google Colab  

---

## 📂 Dataset  
-Dataset: [Fake News Detection (Kaggle)](https://www.kaggle.com/datasets/bhavikjikadara/fake-news-detection)
- News articles labeled as **True (0)** or **Fake (1)**.  
- ~45,000 samples from different sources (2015–2017).  
- Balanced distribution: **Fake News 52.3%**, **True News 47.7%**.  

---

## 🛠 Methodology  
1. **Exploratory Data Analysis (EDA)**  
   - Distribution of Fake vs True News.  
   - Word count analysis & dominant word clouds.  
   - Subject category exploration.  

2. **Text Preprocessing & Feature Engineering**  
   - Stopword removal, lowercasing, punctuation cleaning.  
   - Lemmatization.  
   - TF-IDF vectorization.  
   - Numerical features (e.g., word count).  

3. **Modeling & Evaluation**  
   - Algorithms: **Naive Bayes, Linear SVM, Logistic Regression**.  
   - Evaluation metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC, PR-AUC.  
   - Calibration Curve (Platt Scaling) & Learning Curve analysis.  
   - Hyperparameter tuning with **GridSearchCV**.  

---

## 📊 Key Results  
- **Logistic Regression**: Best model with  
  - Accuracy: **99%**  
  - Precision: **99%**  
  - Recall: **99%**  
  - F1-score: **99%**  
  - ROC-AUC & PR-AUC ≈ **0.999**  
- **Linear SVM**: Stable performance (Accuracy ~98%).  
- **Naive Bayes**: Faster but lower performance (Accuracy ~90%).  
- Calibration improved probability reliability (**Brier Score ↓ 0.0123 → 0.0098**).  

---

## 💡 Insights  
- Fake News articles often highlight **political & sensational keywords** (e.g., *president, hillary, clinton*).  
- True News focuses on **institutional/geographical terms** (e.g., *washington, united, white house*).  
- Peak Fake News activity was observed around **2016–2017 US political events**.  

---

