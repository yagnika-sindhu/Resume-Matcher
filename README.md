# ResumeMatcher – NLP-Powered Resume & Job Description Matching
This project aims to automate the process of matching resumes to job descriptions using Natural Language Processing (NLP) and Machine Learning.

## 🚀 Abstract

Effectively matching resumes with relevant job descriptions is a persistent challenge. We address this by using advanced NLP techniques such as TF-IDF vectorisation and classification models like SVM, Logistic Regression, and ensemble methods (XGBoost, LightGBM, CatBoost).

The final model (XGBoost) achieved:
- ✅ 84.2% Accuracy
- 🎯 0.79 Precision
- 🔁 0.70 Recall
- 📈 AUC: 0.91

## 🛠️ Features

- Preprocessing with lemmatization, stopword removal, etc.
- TF-IDF text vectorisation with bi-grams
- Feature selection using Chi-squared test
- Binary classification: Good Fit vs No Fit
- Ensemble voting classifier for robust performance

## 🧪 Models Compared

| Model               | Accuracy | Precision | Recall | F1-Score |
|--------------------|----------|-----------|--------|----------|
| SVM                | 80.68%   | 0.65      | 0.87   | 0.75     |
| Logistic Regression| 80.26%   | 0.65      | 0.88   | 0.75     |
| **XGBoost**        | **84.20%** | **0.79** | **0.70** | **0.74** |
| LightGBM           | 83.78%   | 0.77      | 0.71   | 0.74     |
| CatBoost           | 82.71%   | 0.78      | 0.67   | 0.72     |
| Voting Classifier  | 80.79%   | 0.66      | 0.86   | 0.75     |

## 📊 Dataset

Sourced from Hugging Face:
[Resume-Job Fit Dataset](https://huggingface.co/datasets/cnamuangtoun/resume-job-description-fit)

## Labels:
- 0 = No Fit
- 1 = Good Fit
  
## 📁 Run the Project

Use the Colab notebook: [Open in Colab](https://colab.research.google.com/drive/1UFwnwgEYHElDvsIN6NN2ikxeNEnWENGw)

