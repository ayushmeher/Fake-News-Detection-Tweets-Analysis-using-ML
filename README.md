# Fake News Detection Using Machine Learning

## Overview
This project aims to develop a machine learning model for distinguishing between fake and true news articles. With the proliferation of misinformation and disinformation online, the ability to automatically identify fake news can be valuable for media consumers, journalists, and researchers. By leveraging natural language processing and machine learning techniques, the project seeks to provide a tool for detecting deceptive content in news articles.

## Data
The dataset used in this project consists of two CSV files: Fake.csv and True.csv. These files contain news articles labeled as either fake or true. Each article includes metadata such as title, text, subject, and date. The data is preprocessed to clean and prepare the text for analysis and model training.

## Approach
The project follows these main steps:
1. **Data Preprocessing:** Text data is cleaned to remove special characters, URLs, punctuation, and numbers. This step helps standardize the text format and improves the quality of features used for classification.
2. **Feature Engineering:** The preprocessed text is transformed into numerical features using techniques like TF-IDF (Term Frequency-Inverse Document Frequency) vectorization. This step converts text data into a format suitable for machine learning algorithms.
3. **Model Training:** Several machine learning models are trained on the transformed text data. These models include Logistic Regression, Decision Trees, Gradient Boosting, and Random Forests. Each model learns to classify news articles as fake or true based on the provided features.
4. **Model Evaluation:** The trained models are evaluated using performance metrics such as accuracy, precision, recall, and F1-score. These metrics help assess the effectiveness of each model in accurately predicting the authenticity of news articles.
5. **Manual Testing:** A function is provided for manual testing, allowing users to input custom news articles and obtain predictions from the trained models. This feature enables users to test the model's performance on real-world news articles outside the dataset.

## Conclusion
The project demonstrates the application of machine learning techniques in identifying fake news articles. By training and evaluating multiple models on a labeled dataset, the project aims to provide a reliable tool for detecting deceptive content online. While no model is perfect, this project contributes to the ongoing efforts to combat misinformation and promote media literacy in the digital age.
