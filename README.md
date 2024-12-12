# Social Media Usage Model

## Overview

This model explores a linear regression model applied to a social media usage dataset. The objective is to predict the number of **Likes_Per_Day** based on features such as **Daily_Minutes_Spent**, **Posts_Per_Day**, and **Follows_Per_Day**.

## Dataset

- **Dataset Name**: Social Media Usage  
- **Number of Records**: 1000  
- **Features**:  
  - **User_ID**: Unique identifier for each user  
  - **App**: The social media platform being used  
  - **Daily_Minutes_Spent**: Total time a user spends on the app each day  
  - **Posts_Per_Day**: Number of posts a user creates per day  
  - **Likes_Per_Day**: Number of likes a user receives daily  
  - **Follows_Per_Day**: Number of new followers a user gains daily  

## Objective

The goal of this model is to predict the **Likes_Per_Day** using linear regression, utilizing the other features as predictors.

## Workflow

1. **Data Exploration**:  
   - Analyzed dataset for feature distributions and correlations.  
   - Calculated mean values for key features for visualization.

2. **Feature Analysis**:  
   - Visualized relationships between features (**Daily_Minutes_Spent**, **Posts_Per_Day**, **Likes_Per_Day**, **Follows_Per_Day**).

3. **Model Training**:  
   - Built a linear regression model using `sklearn`.  
   - Split data into training and testing sets.  
   - Evaluated model performance using Mean Squared Error (MSE) and R² score.

4. **Results**:  
   - Achieved a low R² score (~ -0.01), indicating poor model fit.  
   - Feature coefficients were extracted to understand the impact of each predictor on **Likes_Per_Day**.

## Challenges

- The accuracy of the model is limited due to the relatively small number of records (1000).  
- Low variations in data across social media platforms may hinder trend and pattern detection.  
- Additional features or transformations may be required for better model performance.

## Future Work

- Explore feature engineering or additional data collection to increase the number of records and enhance model accuracy.  
- Experiment with different regression models and hyperparameter tuning.
