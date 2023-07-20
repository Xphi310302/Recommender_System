# Recommender system
This Jupyter Notebook presents a content-based recommender system that provides personalized recommendations for YouTube videos based on demographic information and content features. The notebook demonstrates the process of data loading, preprocessing, exploratory data analysis (EDA), feature engineering, and building different types of content-based recommenders.

## Table of Contents
1. Load Data: This section loads the YouTube video data from a JSON file and stores it in a Pandas DataFrame for further analysis.

2. EDA (Exploratory Data Analysis): The EDA section provides insights into the dataset's structure, including data types, missing values, and category distribution.

3. Missing Value Handling: This section addresses missing values in the dataset by performing listwise deletion and mean/mode imputation for numeric and categorical columns, respectively.

4. Data Modeling: Feature engineering is performed in this section to create new features from existing ones. The focus is on calculating an "engagementRate" metric, and a "point" value is assigned to each video based on its popularity.

5. Data Distribution Visualization: Visualization of data distribution, skewness, and density of key features is presented to better understand the data.

6. Demographic-Based Recommender: This section demonstrates a demographic-based recommender that ranks videos based on their popularity points and filters them according to user-specified categories.

7. Content-Based Recommender: In this section, a content-based recommender is built using Natural Language Processing (NLP) techniques. The recommender uses TF-IDF vectorization to analyze the text data (title, username, and category) of videos and recommends similar videos based on cosine similarity.

8. Title, Username, and Category-Based Recommender: Another content-based recommender is developed in this section. It combines the "title," "username," and "category" features into one feature called "soup" and then computes recommendations based on the cosine similarity between TF-IDF vectors of the "soup."

## Requirements
- Python 3.x
- Jupyter Notebook
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-learn
- Pyvi (Vietnamese tokenizer)
## Usage
To use this notebook, make sure you have the required libraries installed. The notebook can be run in Jupyter Notebook or Jupyter Lab. Simply execute each cell sequentially to observe the output and results at each step. The notebook demonstrates different content-based recommenders and provides personalized recommendations for YouTube videos based on demographic and content information.
