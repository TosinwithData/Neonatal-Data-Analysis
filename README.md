# Birth Data Analysis and Multilinear Regression

This repository contains a Python script for analyzing birth-related data and performing statistical modeling using correlation analysis and multilinear regression. The project focuses on identifying relationships between various factors such as gestational age, mother's age, parity, socioeconomic status, and key birth metrics like OFC (Occipital Frontal Circumference), birth weight, and length.

## Features

- **Data Preprocessing**: Detects file encoding and cleans the dataset by removing null values in key columns.
- **Correlation Analysis**: Computes Pearson correlation coefficients for key variables:
  - Mother's Age vs. OFC
  - Parity vs. OFC
- **Multilinear Regression Models**: Fits and summarizes regression models for:
  - **OFC**: Predicting Occipital Frontal Circumference.
  - **Birth Weight**: Predicting birth weight in grams.
  - **Length**: Predicting length in centimeters.
- **Results Export**: Outputs regression summaries and correlations to a CSV file.

## Tools & Libraries Used

- **Python**: Core programming language.
- **Pandas**: Data manipulation and preprocessing.
- **Scikit-learn**: Statistical and machine learning utilities.
- **Statsmodels**: Building and summarizing multilinear regression models.
- **SciPy**: Statistical functions, including correlation computation.
- **Chardet**: File encoding detection.

## Project Goals
The primary objective of this project is to explore and quantify the relationships between maternal, fetal, and socioeconomic factors, helping researchers and practitioners derive meaningful insights into birth outcomes.
Contributions
Contributions are welcome! Feel free to open issues or submit pull requests to enhance this project.
