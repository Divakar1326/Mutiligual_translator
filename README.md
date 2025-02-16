Multilingual Translator and Machine Learning Model Evaluation with Streamlit

This project involves the development of a Streamlit-based web application that supports multilingual translation, text-to-audio conversion, and the evaluation of various machine learning models. The application integrates several Python libraries to provide an interactive and user-friendly experience for users.

Key Features:
Multilingual Translation: Translate text into multiple languages using the GoogleTranslator API.

Text-to-Audio Conversion: Convert translated text into audio using the gTTS library.

Interactive Model Evaluation: Support for clustering, regression, and classification models, allowing users to train and evaluate machine learning models.

Voice-to-Text Feature: Capture audio input from users and convert it to text.

Data Scaling and SMOTE: Scale features and apply SMOTE for handling imbalanced datasets.

Visualization: Generate interactive plots for data insights and model evaluation.

Functionality:
Multilingual Translation:

Translate input text into a selected target language using the GoogleTranslator API.

Romanize translated text for easier reading.

Convert translated text into audio using the gTTS library.

Interactive Model Evaluation:

Clustering: Implement KMeans clustering to group data points based on similarities.

Regression: Train and evaluate Linear Regression models for predicting continuous variables.

Classification: Support multiple classification algorithms such as Logistic Regression, Naive Bayes, SVM, and KNeighborsClassifier.

Voice-to-Text: Capture audio input from users and convert it to text for translation.

Data Preprocessing:

Handle missing values and encode categorical features using LabelEncoder.

Scale numerical features using StandardScaler.

Apply SMOTE to handle imbalanced datasets and ensure balanced class distribution.

Visualization:

Generate heatmaps for correlation matrices.

Display interactive plots using Plotly for data insights and model evaluation.

Show confusion matrices for classification model performance evaluation.

Technical Details:
Programming Language: Python

Libraries Used:

streamlit for creating the web application

numpy and pandas for data manipulation and analysis

seaborn and matplotlib.pyplot for visualizations

sklearn for machine learning models and preprocessing

imblearn for handling imbalanced datasets using SMOTE

GoogleTranslator for multilingual translation

gTTS for text-to-audio conversion

transliterate for Romanizing translated text

speech_recognition for voice-to-text conversion
