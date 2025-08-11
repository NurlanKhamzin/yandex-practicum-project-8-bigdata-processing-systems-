# 🏡 Project Overview
In this project, you’ll train a linear regression model using data on housing in California from the year 1990. You’ve already worked with this dataset in the fourth module of the course.

## 📊 Dataset Columns:
- longitude — longitude
- latitude — latitude
- housing_median_age — median age of residents in the housing block
- total_rooms — total number of rooms in homes within the block
- total_bedrooms — total number of bedrooms in homes within the block
- population — number of people living in the block
- households — number of households in the block
- median_income — median income of residents in the block
- median_house_value — median house value in the block
- ocean_proximity — proximity to the ocean (categorical)

## 🎯 Goal
Using the data, predict the median house value (median_house_value) for each housing block. Train the model and make predictions on a test set. Evaluate model performance using the following metrics:
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- R² (Coefficient of Determination)

## 🧭 Project Instructions
### 1. Initialize a local Spark session.
### 2. Read the contents of the file:
 - /datasets/housing.csv
### 3. Display the data types of the dataset columns using PySpark methods.
### 4. Preprocess the data:
- Check for missing values and fill them with values of your choice.
- Apply One Hot Encoding to the categorical column (ocean_proximity).
### 5. Build two linear regression models using different datasets:
- One using all columns from the file.
- One using only numerical variables, excluding categorical ones.
Use the LinearRegression estimator from the MLlib library.
### 6. Compare the performance of both models using:
- RMSE
- MAE
- R²
Write conclusions based on the comparison.

## ✅ Project Evaluation Criteria
Reviewers will assess your project based on:
- Completion of all steps in the instructions
- Use of Spark for reading and manipulating data
- Application of MLlib transformers for data preprocessing
- Construction of two linear regression models on different datasets
- Project structure and organization
- Code cleanliness and clarity
- Everything you need to complete this project is covered in the course lessons.

Good luck! 🍀
