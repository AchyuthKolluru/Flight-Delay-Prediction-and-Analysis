# Flight-Delay-Prediction-and-Analysis

## Overview

This project focuses on building a machine learning system to predict flight delays using historical flight data. By utilizing a variety of machine learning models, data preprocessing techniques, and **PySpark** for parallelized data processing, this project provides insights into factors contributing to flight delays and aims to predict delays based on various features. The project was designed to handle large datasets efficiently and deliver real-time predictions.

## Key Features

- **Data Preprocessing**: Comprehensive handling of missing values, categorical encoding, and feature engineering.
- **Model Selection**: Applied multiple machine learning models including Random Forest, XGBoost, and Linear Regression.
- **Performance Evaluation**: Model performance was assessed using metrics like accuracy, precision, recall, F1 score, and confusion matrices.
- **Parallelization**: Leveraged **PySpark** for distributed data processing, ensuring efficient computation with large datasets.
- **Scalability**: Ensured the system can handle a substantial amount of flight data and scale for real-world use cases.

## Tech Stack

- **Python**
  - **Libraries**: Pandas, Scikit-learn, PySpark, Matplotlib, Seaborn
  - **Machine Learning**: Random Forest, XGBoost, Linear Regression
  - **Data Processing**: PySpark for parallelized data handling

## Project Workflow

### 1. Data Acquisition
- Used publicly available flight datasets containing historical information about flight schedules, delays, weather conditions, and airline details.

### 2. Data Preprocessing
- Handled missing data using imputation and removal techniques.
- Categorical variables such as airline codes, flight status, and airport information were encoded into numerical formats using label encoding and one-hot encoding.
- Created new features (e.g., day of the week, time of day) to enhance predictive power.

### 3. Model Training and Evaluation
- Trained multiple models including **Random Forest**, **XGBoost**, and **Linear Regression** to predict the likelihood of a flight being delayed.
- Evaluated models using standard classification metrics: **accuracy**, **precision**, **recall**, **F1 score**, and **confusion matrix**.

### 4. Parallelization and Scaling
- The dataset was large enough to require efficient computation. **PySpark** was employed for distributed data processing, enabling faster model training and data manipulation.
- Leveraged Spark’s `DataFrame` API to handle large datasets in parallel, reducing computation time significantly.

### 5. Insights and Visualization
- Used **Matplotlib** and **Seaborn** for data visualization, providing insights into trends, correlations, and important features related to flight delays.
- Visualized model performance and prediction outcomes.

## Results

- **Accuracy**: Achieved high accuracy in predicting flight delays with models like Random Forest and XGBoost.
- **Feature Importance**: Key factors contributing to delays were identified, such as weather conditions, day of the week, and flight distance.
- **Real-time Potential**: The project demonstrates the potential to integrate real-time data for live flight delay predictions.

