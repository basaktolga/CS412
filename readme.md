# Homework Score Prediction Project

## Overview of the Repository

This repository is dedicated to a machine learning project that aims at predicting homework scores using various regression models. Below is a breakdown of the primary scripts and code pieces along with their functions:

- **Data Preparation Script**: This script is responsible for cleaning and preprocessing the raw data. It includes handling missing values, encoding categorical variables, and normalizing the data.
- **Model Training Scripts**: A collection of scripts, each corresponding to a different regression model - Decision Tree Regressor, Random Forest Regressor, Gradient Boosting Regressor, K-Nearest Neighbors Regressor, Support Vector Regressor, ElasticNet, Ridge Regressor, Lasso Regressor, and a Neural Network Regressor. These scripts involve setting up the models, training them with the dataset, and saving the trained models.
- **Model Evaluation Script**: This script evaluates each model's performance using metrics such as Mean Squared Error (MSE) and R2 Score. It also includes code for cross-validation.
- **Visualization Scripts**: These scripts are used for generating various visualizations to analyze the data and interpret the models' performance. This includes plots for error metrics, feature importance, and model comparison charts.

## Methodology

The project follows a structured approach:

1. **Data Preparation**: The initial step involves rigorous data cleaning and preprocessing to ensure the quality and suitability of the data for modeling.
2. **Model Training**: Various regression models are trained on the dataset. Each model is carefully tuned for its hyperparameters to ensure optimal performance.
3. **Model Evaluation**: The models are evaluated based on performance metrics. Special attention is given to both the accuracy and the generalizability of the models.
4. **Visualization and Interpretation**: Results from the models are visualized for better understanding. This step is crucial for interpreting the models' performance and making data-driven decisions.

In this project, we thought about adding new features to the dataframe to increase the scores for each machine learning algorithm. The words we were able to come up with to increase the scores were:

- **[sorry]**: We assumed that the use of this word signals that the ChatGPT did not properly understand the essence of the question the user is asking.
- **[oversight]**: Similar to the above, we thought that ChatGPT mentions its ov oversight when stated by the user.
- **[apologize]**: The ChatGPT also apologizes a lot when it is when its cornered and repeatly apologizes.
- **[classifier]**: Our chain of thought was that the users who ask about the 7th question (using classifier) are probably were able to handle the rest. Here, we got our inspiration from the word "Entropy" that were previously given.

We observed small improvements for some machine learning algorithms, but  

## Results

The results section presents a detailed analysis of the models' performance. This includes:

- **Performance Metrics**: Tables and charts showing the MSE and R2 Score for each model, providing a clear comparison of their effectiveness.
- **Model Comparison**: A comparative analysis of all the models, highlighting their strengths and weaknesses in the context of the project.
- **Feature Importance Analysis**: Visualizations showing the importance of different features in the predictive models, offering insights into what drives homework scores.
- **Error Analysis**: Plots and discussions around the error patterns observed in the predictions, which are crucial for understanding model limitations.

## Team Contributions

- **Ahmet Melih Afşar**: Developed the Neural Network model.
- **Agit Sefkan Balcı**: Worked on the implementation and evaluation of Ridge and Lasso models.
- **Emre Bülbül**: Responsible for the Gradient Boosting and KNN models.
- **Tolga Başak**: Did research on ElasticNet and how it could be added to this project.
- **Ulaş Meriç**: Implemented Support Vector Machine Regression method.

---
