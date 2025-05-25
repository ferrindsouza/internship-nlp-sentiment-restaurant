# Sentiment Analysis of Restaurant Reviews (Internship Project)

![Internship Project](https://img.shields.io/badge/Project-Type%3A%20Internship%20%7C%20Machine%20Learning-blue)
![Python](https://img.shields.io/badge/Language-Python-yellow?logo=python)
![NLP](https://img.shields.io/badge/Tech-NLP-green)
![Scikit-Learn](https://img.shields.io/badge/Library-scikit--learn-orange)

## Overview

This repository documents the work done during my internship as a **Machine Learning Intern** at **Knowledge Solutions India (KSI)** from **June 15, 2020 to July 27, 2020**.

The core focus of the internship project was to develop a **Natural Language Processing (NLP)**-based **sentiment analysis model** to classify restaurant reviews as **positive** or **negative**. This involved building and evaluating various supervised learning models using Python and common NLP libraries.

## About the Organization

**Knowledge Solutions India (KSI)** is a training and certification company that partners with universities and colleges across India. As **Microsoft Authorized Education Partners** and **Certiport CATC**, they provide globally recognized certifications from Microsoft, Apple, Adobe, EC Council, Autodesk, and more. The team at KSI comprises experienced and certified subject matter experts passionate about delivering impactful learning experiences.

## Project Objective

To create a **machine learning model** that can accurately classify the **sentiment** of restaurant reviews using **NLP techniques**. This involved:
- Exploring multiple algorithms
- Preprocessing and vectorizing textual data
- Evaluating model accuracy
- Selecting the best-performing model

## Methodology

The steps carried out during the internship included:

1. **Importing Dataset**  
   - Used a dataset of restaurant reviews for binary classification (positive/negative sentiment).
   - Dataset has 10000 rows and 8 columns.
   - We have to predict whether a review is "Positive" or "Negative".

2. **Preprocessing**  
   - Text cleaning (lowercasing, removing punctuation, etc.)
   - Tokenization and stopword removal
   - Lemmatization
   - **PortStemmer** method has been used for Stemming.
   - I have also tried WordEmbedding with **LSTM**.

3. **Vectorization**  
   - Employed techniques like **Bag-of-Words (BoW)** or **TF-IDF** for numerical representation of text.

5. **Model Training & Evaluation**  
   Models implemented:
   - **Multinomial Naive Bayes**
   - **Bernoulli Naive Bayes**
   - **Logistic Regression**
   - **LSTM**
   - **Bi-Directional LSTM**
   - **RandomForestClassifier**
   - **SVM** and **KNN**.

   Performance was evaluated using metrics such as:
   - Accuracy
   - Precision
   - Recall
   - F1 Score

6. **Result Analysis**  
   - Compared performance of all models to identify the most accurate one.
   - Documented findings and suggested further improvements.

## **Details**
* From this Dataset, To Perform NLP Project, I decided to take **"Review"** and **"Rating columns"**.
* Later After cleaning the columns, I converted **"Rating"** Column, which is actually a numerical column, into the column that has two labels **"Positive"** and **"Negative"**.
* I considered Rating **Above 3** as **"Positive"** and **Below 3** as **"Negative"**.

## Outcome

✅ Successfully built and evaluated multiple ML models  
✅ Improved accuracy using proper text preprocessing techniques  
✅ Gained practical experience in applying NLP to real-world data  
✅ Delivered results within the internship timeline

## Skills Developed

- Natural Language Processing (NLP)
- Supervised Machine Learning
- Python (Scikit-learn, NLTK)
- Model evaluation and selection
- Communication and teamwork in a professional setting
- Time and task management

## Internship Takeaways

This internship gave me:
- Real-world exposure to solving classification problems using machine learning.
- An opportunity to apply theoretical knowledge in a practical environment.
- Improved technical and soft skills like communication, collaboration, and planning.

## Project Artifacts

- 📄 [`Internship_Report.pdf`](https://github.com/ferrindsouza/internship-nlp-sentiment-restaurant/blob/main/INTERNSHIP_REPORT.pdf)
- 📊 [`Sentiment_Analysis_Results.ppt`](https://github.com/ferrindsouza/internship-nlp-sentiment-restaurant/blob/main/INTERNSHIP_PRESENTATION.pdf)

---

## Credits

📌 **Intern:** Ferrin Dsouza  
🔗 **LinkedIn:** [https://www.linkedin.com/in/ferrindsouza](https://www.linkedin.com/in/ferindsouza)
