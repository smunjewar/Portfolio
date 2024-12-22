Movie Recommendation System

Author: Sheetal Munjewar
Course: Bellevue University - DSC550
Project Overview

This project implements a Movie Recommendation System using content-based filtering, collaborative filtering, and a hybrid model approach. It leverages datasets from Grouplens.org and Kaggle.com to provide personalized movie suggestions based on user preferences.
Features

    Content-Based Filtering - Recommends movies using features like genres, overview, and tagline with cosine similarity.
    Collaborative Filtering - Predicts ratings based on user behavior and similar preferences using the Surprise Library.
    Hybrid Model - Combines content-based and collaborative filtering for enhanced recommendations.

Requirements - 

Make sure you have the following installed:

    Python 3.x
    Pandas
    NumPy
    Scikit-learn
    Surprise Library
    Matplotlib
    Jupyter Notebook or any IDE supporting Python

Dataset Sources

    Ratings Data: Grouplens
    Movie Metadata: Kaggle

Installation Instructions

    Clone Repository:

git clone [<repository_url>](https://github.com/smunjewar/Portfolio.git)

Install Dependencies:

    pip install -r requirements.txt

    Download Datasets:
        Place the datasets in the data/ directory.

Execution Instructions
    Open the Jupyter Notebook:

jupyter notebook

Navigate to the project notebook:

    Movie_Recommendation_System.ipynb

    Follow the steps inside the notebook to load datasets, preprocess data, and build models.

File Descriptions

    movie_recommendation.ipynb - Contains the main code and model implementation.
    data/ - Folder to store datasets.
    models/ - Folder to save pre-trained models.
    README.md - Project instructions and documentation.

Results

    Developed multiple recommendation models, including content-based and collaborative filtering.
    Achieved 93% accuracy with collaborative filtering.
    Built a hybrid model integrating weighted ratings and collaborative filtering for improved recommendations.

Future Improvements

    Incorporate deep learning techniques for enhanced predictions.
    Optimize scalability for larger datasets.
    Implement real-time recommendation features.

Contact Information

    GitHub Profile: https://smunjewar.github.io/Portfolio/
    