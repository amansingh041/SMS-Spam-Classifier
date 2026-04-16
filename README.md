## SMS Spam Classifier

This project is a Machine Learning-based SMS Spam Detection system that classifies text messages as Spam or Ham (Not Spam) using Natural Language Processing (NLP) techniques.

The model is trained on a labeled SMS dataset and applies text preprocessing, feature extraction, and classification algorithms to achieve high accuracy in detecting unwanted messages.

### Live Demo : https://sms-spam-webapp.onrender.com

### Project Overview

Unwanted spam messages are a common problem in digital communication. This project builds a robust classifier that automatically detects spam SMS using Natural Language Processing (NLP) and Machine Learning algorithms.

The system processes raw text input, converts it into numerical features using TF-IDF, and predicts whether a message is spam or not.

### Key Features

Classifies SMS into Spam or Ham
Advanced text preprocessing:
    Lowercasing
    Tokenization
    Stopword removal
    Porter Stemmer
    Feature extraction using TF-IDF Vectorization
Multiple ML models implemented:
    Multinomial Naive Bayes
    Support Vector Classifier (SVC)
    Random Forest Classifier
    Extra Trees Classifier
Performance evaluation:
    Accuracy
    Precision
    Recall
    Confusion Matrix

### Project Workflow
1. Data Collection (SMS Dataset)
2. Data Cleaning & Preprocessing
3. Text Normalization (Porter Stemmer)
4. Feature Extraction (TF-IDF)
5. Model Training
6. Model Evaluation
7. Prediction on New Data

### Technologies Used

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
NLP (Natural Language Processing)

### Model Performance (Example)
Random Forest Classifier Model
    Training Accuracy: 97.58%
    Testing Accuracy: 99.97%
    Precision: 100%
    Recall: 99.8%

### Future Improvements
Deploy as a web application using Flask
Real-time SMS spam filtering system
Implement Deep Learning models 
Improve handling of imbalanced datasets 

### Use Cases
1. Spam filtering in messaging apps
2. Email/SMS security systems
3. Customer communication analysis
4. NLP-based classification systems

### Conclusion

This project highlights how Machine Learning and NLP can be effectively applied to detect spam messages, improving communication quality and user safety. It also demonstrates strong practical skills in building and evaluating real-world ML models.