# UConn-Senior-Design-Offensive-Content-Filter
Machine learning component for detecting offensive content in a campus safety app, using SVM and TF-IDF.

This repository contains the **Offensive Content Filter** component of a campus safety app created as part of my Senior Design Project at UConn. The filter uses **Support Vector Machine (SVM)** with **TF-IDF vectors** to detect and block offensive content in user-generated reports.

## Purpose:
The content filter was designed to proactively prevent the posting of offensive content in the app, promoting a safe and inclusive environment for students to report suspicious events.

## Features:
- **SVM (Support Vector Machine)** model to classify text data as offensive or non-offensive.
- **TF-IDF (Term Frequency-Inverse Document Frequency)** for feature extraction from text data (tweets in this case).
- **Text Preprocessing**: Removal of stopwords, punctuation, and URL normalization to ensure accurate classification.

## Dataset:
The dataset consists of **tweets**, each labeled as offensive (1) or non-offensive (0). It includes 24,818 labeled instances, with tweets preprocessed for text classification tasks.

## Technologies Used:
- **Python**: Programming language used to develop the model and preprocess text data.
- **scikit-learn**: For building the SVM model and performing feature extraction with TF-IDF.
- **Pickle**: The trained model was saved as a pickle file and integrated into the app's backend for real-time content moderation.

## Note:
This repository only contains the Offensive Content Filter component. The full app was developed as part of a larger senior design project, which integrates this feature for real-time content moderation within the app.
