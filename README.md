# Resume Screening using Machine Learning

## Project Overview
This project uses Machine Learning and Natural Language Processing (NLP) to classify resumes into different job categories based on the resume content.

## Dataset
The project uses a resume dataset containing resume text and corresponding job categories.

## Workflow
- Data loading and exploration
- Analysis of resume categories
- Class balancing using oversampling
- Resume text preprocessing and cleaning
- Removal of URLs, hashtags, mentions, special characters, punctuation, and non-ASCII characters
- Train-test split
- Text vectorization using TF-IDF
- K-Nearest Neighbors (KNN) model building
- Multi-class classification using One-vs-Rest
- Prediction on test data
- Model evaluation using accuracy, classification report, and confusion matrix
- Prediction of categories for new incoming resumes

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Natural Language Processing (NLP)
- Regular Expressions (Regex)
- Jupyter Notebook / Google Colab

## Machine Learning Algorithm
K-Nearest Neighbors (KNN)

## Feature Extraction
TF-IDF (Term Frequency-Inverse Document Frequency)

## Model Evaluation
The model performance is evaluated using:
- Accuracy
- Classification Report
- Confusion Matrix

## Prediction
The trained model can predict the appropriate job category for a new incoming resume.
