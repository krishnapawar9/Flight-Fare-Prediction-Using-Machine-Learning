# Flight-Fare-Prediction-Using-Machine-Learning
A project to predict flight prices for various airlines based on a Kaggle dataset.

## 📝 Overview

This project focuses on building a machine learning model to predict flight fares. Using a dataset containing flight details such as airline, date of journey, source, destination, and other features, I have performed extensive data preprocessing, exploratory data analysis (EDA), and model training to forecast ticket prices. The final model demonstrates a strong ability to predict flight fares with a high degree of accuracy.

The project is structured to be easily reproducible, with all the code, data, and model artifacts organized in a logical manner.

## 🚀 Key Features

  * **Comprehensive Data Cleaning and Preprocessing:** Handled missing values, formatted date and time columns, and extracted relevant features like month, day, and journey duration from the raw data.
  * **Exploratory Data Analysis (EDA):** Visualized key relationships between features and the target variable (`Price`). The `heatmap.jpg` file provides a clear visualization of feature correlations.
  * **Feature Engineering:** Created new, more informative features from the raw data to improve model performance.
  * **Machine Learning Model Development:** Trained a robust regression model to predict flight prices.
  * **Model Evaluation:** Evaluated the model's performance using appropriate metrics and techniques.
  * **Prediction and Submission:** Generated predictions for the test set and created a submission file (`Sample_submission (1).xlsx - Sheet1.csv`).
  * **Model Persistence:** Saved the trained model using `pickle` for easy deployment and future use.

## 📊 Project Structure

A well-organized repository helps others understand your work.

```
.
├── Flight Price Prediction.ipynb       (The main Jupyter notebook with all the code and analysis)
├── data/
│   ├── Data_Train (1).xlsx - Sheet1.csv
│   ├── Test_set (1).xlsx - Sheet1.csv
│   └── Sample_submission (1).xlsx - Sheet1.csv
├── assets/
│   └── heatmap.jpg
├── models/
│   └── flight_price_predictor.pkl     (The trained model file)
├── Cleaned_flight_fare.xls             (Intermediate cleaned data file)
├── Test_Set_Submissions.xls            (Intermediate predictions file)
└── README.md
```

## 🛠️ Skills and Technologies

This project demonstrates proficiency in the following tools and libraries:

  * **Programming Language:** Python
  * **Data Manipulation & Analysis:** Pandas, NumPy
  * **Machine Learning:** Scikit-learn
  * **Data Visualization:** Matplotlib, Seaborn (as suggested by the `heatmap.jpg`)
  * **Notebook Environment:** Jupyter Notebook

The `heatmap.jpg` visualization was particularly useful in identifying the most influential features, which guided the feature engineering process.

## ✒️ Author

**Krishna Pawar**

  * https://www.linkedin.com/in/krishna-pawar-842903230/
  * https://github.com/krishnapawar9
  * https://www.hackerrank.com/profile/09krishnapawar
  * https://leetcode.com/u/krishna_pawar09/

-----
