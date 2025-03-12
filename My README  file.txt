# Fake News Detection

 Introduction
This project aims to tackle the growing issue of fake news propagation on digital platforms by utilizing machine learning techniques to classify news articles as either real or fake. Fake news is a major societal concern as it can mislead the public and influence critical decisions. This study uses the WELFake dataset, which comprises labeled news articles from various sources. The primary goal is to develop and evaluate different machine learning models, including Logistic Regression, Naive Bayes, Decision Trees, and Long Short-Term Memory (LSTM) networks, for effective fake news detection.

Dataset Overview
The project utilizes the WELFake Fake News Classification dataset, which contains 72,134 news articles, divided into 35,028 real news articles and 37,106 fake news articles. The dataset is an aggregation of four well-known news datasets: Kaggle, McIntire, Reuters, and BuzzFeed Political. The inclusion of diverse sources enhances the robustness of classifiers and prevents overfitting.

Dataset Structure:
- Serial Number: A unique identifier starting from 0.
- Title: The headline of the news article.
- Text: The content of the news article.
- Label:
  - `0` - Fake News
  - `1` - Real News

The dataset consists of 78,098 data entries, but only 72,134 entries are utilized for training and testing.

Methodology
Data Preprocessing & Exploratory Data Analysis
Before training machine learning models, the dataset undergoes extensive preprocessing, including:
- Removing stopwords, punctuations, and special characters
- Tokenization and lemmatization
- Analyzing word frequency, text length, and class distribution

Machine Learning Models Implemented
The study evaluates the following models:
1. Logistic Regression: A baseline linear model for binary classification.
2. Naive Bayes: A probabilistic classifier based on Bayes' theorem.
3. Decision Trees: A tree-based model for classification tasks.
4. Long Short-Term Memory (LSTM): A deep learning model designed to capture long-term dependencies in text.

 Model Evaluation Metrics
To assess the effectiveness of the models, we use the following metrics:
- Accuracy
- Precision
- Recall
- F1-Score

 Results & Findings
The evaluation results demonstrate that the LSTM model achieved the highest accuracy of 95.32%, indicating strong performance in detecting false positives. Other models also performed well, but LSTM outperformed them in handling complex textual patterns.

Key Findings:
- Traditional machine learning models like Logistic Regression and Naive Bayes perform well but struggle with complex patterns in text.
- LSTM-based deep learning models significantly improve classification accuracy by capturing long-term dependencies in news content.
- Text preprocessing techniques such as tokenization and stopword removal enhance model performance.

 Conclusion
This project provides a robust fake news detection framework that can be beneficial for news organizations, social media platforms, and policymakers. By leveraging machine learning and deep learning techniques, the study contributes to the fight against misinformation.

 References
Published in: IEEE Transactions on Computational Social Systems, pp. 1-13. DOI: [10.1109/TCSS.2021.3068519](https://doi.org/10.1109/TCSS.2021.3068519).



