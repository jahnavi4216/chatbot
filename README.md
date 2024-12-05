# HealthCare ChatBot - Disease Prediction and Consultation System

This repository contains a healthcare chatbot system that predicts possible diseases based on symptoms entered by the user. The system utilizes machine learning algorithms to predict the disease and provides information, severity, precautions, and recommendations for consultation based on the symptoms provided by the user.

## Features

- **Disease Prediction**: The system predicts potential diseases based on the symptoms provided by the user using machine learning classifiers (Decision Tree, SVM).
- **Symptom Severity**: Provides information on the severity of the symptoms and suggests if a consultation with a doctor is needed.
- **Symptom Description**: Gives detailed descriptions of the symptoms that the user inputs.
- **Precautionary Measures**: Offers precautionary steps for managing the disease.
- **Interactive Chatbot**: The system allows users to interact through a command-line interface, asking for symptoms and days of experience.

## Requirements

- Python 3.x
- pandas
- sklearn
- pyttsx3
- numpy
- re
- csv

You can install the required libraries by running the following command:

```bash
pip install -r requirements.txt
pandas==1.5.3
scikit-learn==1.2.1
pyttsx3==2.90
numpy==1.23.5

