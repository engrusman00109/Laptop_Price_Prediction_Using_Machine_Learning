# Laptop Price Prediction Using Machine Learning

## Problem Statement
The goal of this project is to predict the prices of laptops based on various features such as brand, RAM, storage, screen size, etc. By leveraging machine learning techniques, we aim to build a robust model that can accurately estimate the price of a laptop.

## Steps of the Project
1. **Data Collection**
    - Gathered a comprehensive dataset of laptop specifications and their prices from various online sources and repositories.

2. **Data Cleaning**
    - Handled missing values through imputation.
    - Corrected inconsistencies and errors in the data, such as incorrect or duplicate entries.

3. **Data Preprocessing**
    - Encoded categorical variables using techniques such as one-hot encoding.
    - Scaled numerical features to ensure uniformity across the dataset.

4. **Exploratory Data Analysis (EDA)**
    - **Univariate Analysis**: Examined the distribution of individual features to understand their spread and central tendency.
    - **Bivariate Analysis**: Analyzed the relationship between pairs of features to identify correlations.
    - **Multivariate Analysis**: Explored interactions between multiple features to uncover complex relationships.

5. **Feature Engineering**
    - Created new features based on existing data to improve model performance.
    - Selected the most relevant features for model training through techniques like feature importance and correlation analysis.

6. **Model Building**
    - Developed and evaluated multiple regression models:
        - Linear Regression
        - Ridge Regression
        - Lasso Regression
        - KNN
        - Decision Tree
        - SVM
        - Random Forest
        - ExtraTree
        - GradientBoost
        - XGBoost
        - AdaBoost
        - Voting Regressor
        - Stacking

7. **Model Evaluation**
    - Assessed model performance using metrics such as R² score and Mean Absolute Error (MAE).
    - Achieved an R² score of 0.8781 and a Mean Absolute Error (MAE) of 0.1667 with the stacking model.

8. **Model Deployment**
    - Deployed the stacking model using Streamlit to create an interactive web application.


## Results
The stacking model achieved an R² score of 0.8781 and a Mean Absolute Error (MAE) of 0.1667, demonstrating its effectiveness in predicting laptop prices based on the provided features.

## Conclusion
This project successfully built and deployed a machine learning model to predict laptop prices. The use of various regression models and the deployment of the stacking model through Streamlit provided an interactive and accurate tool for price estimation.

## Future Work
- Further refine the model by incorporating more features and larger datasets.
- Implement additional machine learning techniques to improve prediction accuracy.
- Enhance the Streamlit application with more functionalities and user-friendly features.

