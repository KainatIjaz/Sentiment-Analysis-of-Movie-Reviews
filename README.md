# 🎭 Sentiment Analysis of Movie Reviews  

## 📌 Overview  
This project applies **Natural Language Processing (NLP)** techniques to classify **IMDB movie reviews** as **positive or negative** using machine learning models.  
By  text preprocessing, TF-IDF vectorization, and multiple classification algorithms, the project aims to improve sentiment prediction accuracy.  

## 📂 Dataset  
📌 **Source:** [IMDB Movie Reviews Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)  
- **50,000** movie reviews labeled as **positive (1) or negative (0)**.  
- Text-based data for sentiment classification.  

## 🛠 Tools & Technologies  
🔹 Python | Scikit-learn | NLP | TF-IDF | Machine Learning | Jupyter Notebook  

## 🔍 Methodology  
1️⃣ **Data Preprocessing**  
   - Text lowercasing, HTML tag removal, punctuation removal, and stemming.  
   - Sentiment encoding (positive → 1, negative → 0).  

2️⃣ **Feature Engineering**  
   - **TF-IDF Vectorization** to convert text into numerical format.  

3️⃣ **Model Training & Evaluation**  
   - **Multinomial Naïve Bayes** (Accuracy: **86%**)  
   - **Logistic Regression** (Accuracy: **89%**)  
   - **Linear SVC** (Accuracy: **90%**)  

4️⃣ **Performance Analysis**  
   - Confusion matrices & classification reports for precision, recall, and F1-score.  

## 📈 Results & Insights  
✔ **Linear SVC achieved the highest accuracy (90%)**, making it the best-performing model.  
✔ Logistic Regression performed similarly with **89% accuracy**.  
✔ **Multinomial Naïve Bayes (86%)** was computationally efficient but slightly less accurate.  

## 🚀 How to Run  
1. **Install dependencies:**  
   ```bash
   pip install pandas scikit-learn nltk
