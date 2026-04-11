# Fraudulent Job Posting Detection

This project uses Machine Learning to detect fraudulent job postings based on job-related features.

## Objective
To build a classification model that identifies fake job listings and helps prevent job scams.

## Features
- Data preprocessing and cleaning
- Handling class imbalance using SMOTE
- Feature engineering
- Model training using XGBoost
- Performance evaluation using F1-score

## Results
- Achieved F1-score of 0.87
- Improved recall on minority (fraudulent) class

## Tech Stack
- Python
- Pandas
- Scikit-learn
- XGBoost
- Imbalanced-learn (SMOTE)

## Dataset
Dataset used for this project:
https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction
It contains real and fraudulent job postings with features like company profile, description, and requirements

## How to Run
1. Install required libraries
2. Run the notebook or Python script
3. Model will train and output evaluation metrics

## Future Improvements
- Deploy model as a web app
- Improve recall further
- Add real-time detection system
