# SpaceX Launch Success Prediction

This project aims to predict the success or failure of SpaceX launches based on various factors such as payload mass, orbit type, and launch site. The analysis leverages machine learning algorithms to build predictive models and provide insights into the factors influencing the success of space launches.

## Project Overview

In this project, we:

- Analyze SpaceX launch data to identify trends and insights.
- Use machine learning algorithms to predict launch success.
- Optimize model performance using hyperparameter tuning with GridSearchCV.
- Evaluate models using accuracy, confusion matrix, F1 score, and Jaccard score.

## Data

The dataset used in this project contains information about SpaceX launches, including:

- **Payload Mass**: The mass of the payload in kilograms.
- **Orbit**: The type of orbit for the mission (e.g., LEO, GEO, etc.).
- **Launch Site**: The site from which the launch occurred (e.g., KSC LC-39A).
- **Launch Success**: Whether the launch was successful or not.

## Technologies Used

- **Python**: The primary language used for data analysis and modeling.
- **Pandas**: Data manipulation and analysis.
- **Scikit-learn**: Machine learning and model evaluation.
- **Matplotlib & Seaborn**: Data visualization.
- **GridSearchCV**: Hyperparameter tuning to optimize model performance.

## Steps

### 1. Data Preprocessing
- Load and clean the dataset.
- Convert categorical features into numerical values using one-hot encoding.
- Standardize the feature data.

### 2. Exploratory Data Analysis (EDA)
- Visualize launch success rates using a count plot.
- Analyze the relationship between payload mass, orbit type, and launch success.

### 3. Model Training and Evaluation
- Split the data into training and testing sets.
- Train multiple machine learning models: Logistic Regression, SVC, Decision Tree, and K-Nearest Neighbors.
- Perform hyperparameter tuning using GridSearchCV to optimize model performance.

### 4. Model Evaluation
- Evaluate models using accuracy, confusion matrix, F1 score, and Jaccard score.
- Determine the best-performing model based on evaluation metrics.

