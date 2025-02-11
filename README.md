# CICIDS2017 & NSL-KDD
This project analyzes network intrusion using the CICIDS2017_Thursday-WorkingHours-Morning-WebAttacks.csv dataset and the NSL-KDD.csv dataset. After preprocessing and cleaning both datasets, multiple machine learning models (KNN, SVM, Naïve Bayes, Random Forest, etc.) were applied. Their performance were compared to determine the most effective model for detecting web attacks.

# Intrusion Detection with Machine Learning

## Overview
This project focuses on analyzing and detecting web attacks using machine learning techniques. The dataset used is **CICIDS2017_Thursday-WorkingHours-Morning-WebAttacks.csv**, which was preprocessed and cleaned before applying multiple classification models.

## Dataset
- **Source:** CICIDS2017 (Canadian Institute for Cybersecurity Intrusion Detection System)
- **File:** `CICIDS2017_Thursday-WorkingHours-Morning-WebAttacks.csv`
- **Contents:** Network traffic data with labels for web attacks.

## Preprocessing
The dataset was cleaned and prepared through:
- Handling missing values
- Feature selection
- Normalization/standardization
- Encoding categorical variables

## Machine Learning Models
The following models were trained and tested:
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**
- **Naïve Bayes**
- **Random Forest**
- **Decision Tree**
- **Neural Network**
- **Logistic Regression**

## Performance Evaluation
Each model was evaluated based on key performance metrics:
- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix

## Conclusion
After comparing the models, the best-performing one was identified based on overall efficiency in detecting web attacks.

## Provided Files

Jupyter Notebooks (.ipynb): Includes the full implementation of preprocessing, model training, and evaluation.

CSV Datasets (.csv): The dataset before and after preprocessing.

Report (.pdf): Detailed documentation of the project, findings, and conclusions.

## Dependencies
Ensure the following Python libraries are installed:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

## License
This project is open-source and available under the [MIT License](LICENSE).

