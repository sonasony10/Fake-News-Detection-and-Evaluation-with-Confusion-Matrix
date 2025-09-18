# 📰 Fake News Detection and Evaluation with Confusion Matrix  

## 📌 Project Overview  
This project focuses on detecting fake news articles using **Natural Language Processing (NLP)** and **Machine Learning** techniques.  
News articles were preprocessed, vectorized using **Word2Vec** and **TF-IDF**, and classified using models such as **Logistic Regression**, **Random Forest**, **AdaBoost**, and **Gradient Boosting**.  
The models were evaluated using **accuracy, precision, recall, F1-score, and confusion matrices** to assess their ability to distinguish fake and true news.  

---

## 👩‍💻 Author  
**Sona Sony**  
M.Sc. Statistics (2023–2025), Nirmala College, Muvattupuzha  
Internship Period: 25th August 2025 – 19th September 2025  
Submitted to: **IDEAS – Institute of Data Engineering, Analytics and Science Foundation, ISI Kolkata**  

---

## 🎯 Objectives  
- Preprocess and clean fake/true news datasets  
- Transform text into numerical representations using **TF-IDF** and **Word2Vec**  
- Train and evaluate classification models (Logistic Regression, Random Forest, AdaBoost, Gradient Boosting)  
- Compare model performances with confusion matrices and evaluation metrics  
- Save trained models for reuse on new datasets  

---

## 🔄 Methodology  
1. **Data Collection**  
   - Fake news from Politifact & Wikipedia  
   - True news from Reuters  
   - Validation dataset from BuzzFeed  

2. **Data Preprocessing**  
   - Removed URLs, punctuation, and special characters  
   - Converted text to lowercase  
   - Dropped duplicates and missing values  
   - Tokenized and normalized  

3. **Vectorization**  
   - **Word2Vec**: captured semantic relationships  
   - **TF-IDF**: captured discriminative word frequencies  

4. **Model Training & Evaluation**  
   - Logistic Regression (Word2Vec)  
   - Random Forest (Word2Vec, TF-IDF)  
   - AdaBoost (TF-IDF)  
   - Gradient Boosting (TF-IDF)  

5. **Model Saving & Deployment**  
   - Models saved using **Pickle**  
   - Reloaded for prediction on new unseen datasets  

---

## 📊 Results  

### Logistic Regression (Word2Vec)  
- Accuracy: **94.12%**  
- Precision: **93.09%**  
- Recall: **94.69%**  
- F1-score: **93.88%**  

### Random Forest (Word2Vec)  
- Accuracy: **96.84%**  
- Precision: **96.79%**  
- Recall: **96.58%**  
- F1-score: **96.69%**  

### Boosting Models (TF-IDF)  
| Model            | Accuracy |
|------------------|----------|
| AdaBoost         | 67.56%   |
| Gradient Boosting | 75.67%  |

📌 **Observation**:  
- Random Forest with Word2Vec achieved the **highest accuracy** (96.84%).  
- Gradient Boosting outperformed AdaBoost when using TF-IDF.  

---

## 📈 Visualizations  
- **Confusion Matrices** to analyze true/false predictions  
- **Bar Charts & Pie Charts** for subject distribution  
- Random samples of fake vs real news highlighted style differences  

---


---

## 📚 References  
- Reuters News Dataset  
- Politifact Fake News Dataset  
- BuzzFeed News Dataset  
- [Scikit-learn Documentation](https://scikit-learn.org)  
- [Gensim Documentation](https://radimrehurek.com/gensim)  
- Shu, K. et al. (2017). *Fake News Detection on Social Media: A Data Mining Perspective*  
- Zhou, X., & Zafarani, R. (2020). *A Survey of Fake News: Fundamental Theories, Detection Methods, and Opportunities*  

---

## 🚀 Future Work  
- Expand dataset with multilingual & real-time sources  
- Experiment with **deep learning models (LSTMs, GRUs, BERT)**  
- Incorporate **author credibility, social media signals, and temporal trends**  
- Enable **continuous retraining** for better adaptability  

---

## 🔗 Repository Link  
👉 [Fake News Detection and Evaluation with Confusion Matrix](https://github.com/sonasony10/Fake-News-Detection-and-Evaluation-with-Confusion-Matrix)


 
