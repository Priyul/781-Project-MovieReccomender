# Movie Recommender System

## Overview
This project is designed to create a recommendation system using the MovieLens 1M dataset, which contains 1 million movie ratings. The system employs data preprocessing, similarity calculations, and matrix factorization techniques to predict user preferences. The project includes features such as data visualization, evaluation metrics, and user-item recommendation pipelines.

##Contents of the Zip File
- project.ipynb: The main Jupyter Notebook containing the code to preprocess data, train the model, and evaluate performance.
- datasets/: A folder to store the dataset files. Please note that the dataset itself is not included in the ZIP file. Users need to upload the necessary .dat files to this directory before running the code.

##Setup Instructions
Environment Requirements:
  - Python 3.7 or later
  - Jupyter Notebook or Google Colab
Install Dependencies:
  Install the required Python libraries using pip:
    - pip install pandas numpy scikit-learn matplotlib seaborn tqdm

##Dataset Preparation:
Download the MovieLens 1M dataset from https://grouplens.org/datasets/movielens/1m/. The dataset includes .dat files such as ratings.dat, movies.dat, and users.dat.
Upload the .dat files into the datasets/ directory or your runtime environment if using Google Colab.

##Running the Code
  - Open project.ipynb in Jupyter Notebook or upload it to Google Colab.
  - Upload the .dat files from the MovieLens 1M dataset and ensure they are in the same directory as the runtime of this project.
  - Execute the notebook cells in order to:
    - Load and preprocess the data.
    - Train the recommendation model using techniques such as Singular Value Decomposition (SVD).
    - Evaluate the model with appropriate metrics
   
##Data Information
The project uses the MovieLens 1M dataset, which contains:
  - ratings.dat: User-item interaction data with user IDs, movie IDs, and ratings.
  - movies.dat: Metadata about the movies, such as titles and genres.
  - users.dat: User demographic information, including age and gender.

##Dataset Preparation
  - Download the dataset from MovieLens 1M dataset.
  - Upload the .dat files into the datasets/ folder in your runtime environment.
  - The notebook contains code to read these .dat files into Pandas DataFrames for preprocessing and analysis. 
