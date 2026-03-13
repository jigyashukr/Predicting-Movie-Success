# Predicting Movie Success Using Machine Learning

## Project Overview

This project focuses on predicting the success of movies using machine
learning techniques. The dataset contains information about various
movie attributes such as reviews, user engagement, duration, and social
media popularity. The goal is to analyze these features and build models
that can predict movie performance.

The project includes data preprocessing, exploratory data analysis,
feature engineering, and machine learning model development for both
regression and classification tasks.

## Objectives

-   Analyze movie-related data to identify important features
    influencing success
-   Perform data cleaning and preprocessing
-   Conduct exploratory data analysis to understand patterns in the
    dataset
-   Build machine learning models to predict movie ratings and
    performance
-   Compare different models based on evaluation metrics

## Dataset Description

The dataset includes multiple attributes related to movies, including:

-   num_critic_for_reviews
-   duration
-   num_voted_users
-   num_user_for_reviews
-   movie_facebook_likes
-   director_facebook_likes
-   genre information
-   other metadata related to movie popularity and reviews

These features help determine the popularity and potential success of a
movie.

## Project Workflow

### 1. Importing Libraries

Essential Python libraries such as pandas, numpy, matplotlib, seaborn,
and scikit-learn are used for data analysis and model building.

### 2. Loading the Dataset

The movie dataset is loaded into a pandas DataFrame for further analysis
and processing.

### 3. Data Preprocessing

-   Handling missing values
-   Removing unnecessary columns
-   Converting data types where necessary
-   Cleaning the dataset for modeling

### 4. Feature Engineering

A new column is created to identify the main genre of each movie. This
helps categorize movies and improve analysis.

### 5. Outlier Detection

Outliers are detected using the Z-score method and removed to improve
model performance.

### 6. Exploratory Data Analysis

EDA is performed to understand relationships between different
variables. Visualizations and statistical summaries are used to identify
trends in movie ratings and popularity.

### 7. Feature Selection

Important features are selected based on correlation and their influence
on the target variable.

### 8. Regression Modeling

Regression models are used to predict movie ratings. Model performance
is evaluated using: - Mean Squared Error (MSE) - Mean Absolute Error
(MAE)

Results show that Linear Regression performs best among the tested
regression models.

### 9. Classification Modeling

Movies are categorized into performance groups such as Hit, Average, and
Flop based on ratings.

Classification algorithms are used to predict the category of a movie.

### 10. Model Evaluation

Different classification models are tested and compared. The Random
Forest Classifier performs the best with an accuracy of approximately 73
percent.

## Technologies Used

-   Python
-   Jupyter Notebook
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Scikit-learn

## Results

-   Linear Regression achieved the best results for rating prediction
    with low MSE and MAE.
-   Random Forest Classifier achieved around 73 percent accuracy for
    movie performance classification.

## Future Improvements

-   Use larger and more recent movie datasets
-   Apply advanced machine learning algorithms such as Gradient Boosting
    or XGBoost
-   Include additional features such as budget, cast popularity, and
    release timing
-   Improve feature engineering and hyperparameter tuning

## How to Run the Project

1.  Clone the repository
2.  Install the required Python libraries
3.  Open the Jupyter Notebook file
4.  Run the cells step by step to reproduce the analysis and results

## Author

This project was developed as part of a machine learning analysis to
understand and predict movie success based on available data.
