# Problematic Internet Use Prediction for Kaggle competition. I need some help with the data preprocessing.  

This project focuses on predicting problematic internet use among children, utilizing survey data and actigraphy time series. Machine learning models, particularly logistic regression, are employed to uncover insights and improve prediction accuracy through careful feature engineering.

## Key Features

- **Data Loading**: Uses `pyarrow` to efficiently load large datasets in Parquet format, minimizing memory overhead.
- **Data Preprocessing**: Handles missing values, performs encoding for categorical variables, and readies the data for training.
- **Actigraphy Feature Engineering**: Extracts time-series based features like total activity duration, movement mean, and standard deviation from the raw actigraphy data.
- **Exploratory Data Analysis**: Summarizes key statistics of the dataset and visualizes distributions to assess skewness and kurtosis in numerical features.
- **Model Training**: Logistic Regression is applied, and model performance is assessed using cross-validation with a custom scoring function (Cohen's Kappa).
- **Submission Generation**: Prepares the final predictions for submission in the appropriate Kaggle format.

