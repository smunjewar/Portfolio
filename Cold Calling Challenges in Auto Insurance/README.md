Cold Calls for Auto Insurance

Project Overview

This project focuses on analyzing and improving cold call strategies for auto insurance marketing. 
It evaluates datasets to identify key factors influencing customer behavior and builds machine learning models 
to predict responses to marketing campaigns.

Dataset
Source: Kaggle - Car Insurance Cold Calls Dataset

Features: Customer demographics, previous interactions, and campaign-specific attributes.

Goal: Predict the likelihood of a customer purchasing auto insurance based on cold call interactions.

Requirements - Python 3.x

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

Installation

Clone the repository:

git clone <repository_url>
cd cold-calls-auto-insurance

Install dependencies:

pip install -r requirements.txt

Download the dataset and save it in the data/ directory.

Execution Instructions

Open Jupyter Notebook:

jupyter notebook

Run the notebook cold_calls_analysis.ipynb step-by-step to preprocess data, train models, and evaluate performance.

Models Evaluated

K-Nearest Neighbors (KNN) - Accuracy: 76%

Logistic Regression - Accuracy: 79%

Naive Bayes Classifier - Accuracy: 71%

Random Forest - Accuracy: 81% (Preferred Model)

Results

Random Forest demonstrated the highest accuracy at 81%, making it the preferred model.

Key insights were derived, showing age, job, and balance as significant predictors.

Future Improvements

Feature engineering to enhance model accuracy.

Experimenting with advanced ensemble methods.

Visualizing decision boundaries for improved interpretability.

Contact

GitHub: https://smunjewar.github.io/Portfolio

LinkedIn: linkedin.com/in/sheetalmunjewar

Acknowledgements

Data sourced from Technical University of Munich (TUM) and Kaggle's Car Insurance Cold Calls Dataset.