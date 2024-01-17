# Weather Prediction Project

## Overview
This project aims to predict weather conditions using a machine learning model based on historical weather data. The dataset used in this project contains information such as temperature, rainfall, humidity, and wind speed for different locations and dates.

## Project Structure
- `notebook.ipynb`: Jupyter Notebook containing the code for data exploration, preprocessing, modeling, and evaluation.
- `weather.csv`: Dataset file containing historical weather data.
- `README.md`: Project documentation.

## Data Exploration
- The dataset was loaded and explored to understand the features and their distributions.
- Missing values were identified and handled using appropriate imputation strategies.

## Data Preprocessing
- Features and target variable were selected for modeling.
- Missing values were imputed using the mean value for numerical features.
- The dataset was split into training and testing sets.

## Model Building
- A Random Forest Regressor was chosen as the machine learning model.
- The model was trained on the training set.

## Model Evaluation
- Mean Absolute Error (MAE) was used to evaluate the performance of the model.
- The MAE was calculated on the test set.

## Conclusion
- The machine learning model demonstrated reasonable predictive performance based on the MAE.
- Predictions were visualized and compared with actual weather conditions for different cities.

## Future Work
- Further feature engineering and model tuning could be explored to improve prediction accuracy.
- Additional models and algorithms could be tested for comparison.

## Dependencies
- Python 3.x
- Jupyter Notebook
- pandas
- scikit-learn
- matplotlib

Feel free to reach out for any questions or improvements!
