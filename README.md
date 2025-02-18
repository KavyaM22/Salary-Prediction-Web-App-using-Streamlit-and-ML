# Salary Prediction Web App

## Overview
This project is a **Salary Prediction Web App** built using **Streamlit** and **Machine Learning**. The application predicts salaries based on user inputs such as job title, years of experience, education level, and location. The goal is to help individuals and HR professionals estimate salaries using data-driven insights.

## Features
- **Interactive Web Interface**: Built using Streamlit, allowing users to enter data easily.
- **Machine Learning Models**: Implements various regression models, including:
  - Linear Regression
  - Decision Trees
  - Random Forest
  - Gradient Boosting
- **User Input Options**: Users can input job-related data, such as:
  - Job Title
  - Years of Experience
  - Education Level
  - Geographic Location
- **Data Visualization**: The app provides insights into salary trends using various visualizations such as histograms, scatter plots, and correlation heatmaps.
- **Model Performance Metrics**: Evaluates models based on:
  - Root Mean Squared Error (RMSE)
  - Mean Absolute Error (MAE)
  - R² Score

## Technologies Used
- **Programming Language**: Python
- **Frameworks & Libraries**:
  - **Streamlit**: For building the interactive user interface.
  - **Scikit-learn**: For implementing machine learning models.
  - **Pandas & NumPy**: For data manipulation and preprocessing.
  - **Matplotlib & Seaborn**: For data visualization.
  - **Joblib**: For saving and loading trained machine learning models.
- **Version Control**: Git & GitHub for collaboration and tracking changes.

## Usage
1. Open the Streamlit web app in your browser.
2. Enter your job details, including **Job Title, Experience, Education Level, and Location**.
3. Click **Predict Salary** to generate an estimated salary based on the input.
4. Explore the provided salary trends and analysis through various charts and tables.

## Model Training and Performance
### Dataset
- The dataset used for training contains salary information across multiple industries and locations.
- Data preprocessing steps include handling missing values, feature encoding, and feature scaling.

### Training Process
- The dataset is split into training (80%) and testing (20%) sets.
- Models are trained using Scikit-learn's regression algorithms.
- Hyperparameter tuning is performed to improve accuracy.

### Best Performing Model
- Based on RMSE and R² Score evaluations, **Gradient Boosting Regressor** performed the best.
- Feature importance analysis identified **Years of Experience, Job Title, and Location** as key predictors.

## Future Enhancements
- **Real-Time Data Updates**: Integrate with APIs to fetch up-to-date salary trends.
- **Advanced Neural Networks**: Explore deep learning techniques for improved accuracy.
- **Deployment on Cloud**: Host the app on platforms like AWS, Heroku, or Google Cloud for wider accessibility.
- **User Authentication**: Add login and profile management for personalized experiences.



