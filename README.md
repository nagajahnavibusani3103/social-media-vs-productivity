# Social Media Usage vs Productivity – Python Project

## Overview
This project analyses the relationship between daily social media usage and self-reported productivity using a public Kaggle dataset. It was developed as part of the Python Fundamentals course to practise basic data handling, visualisation and a simple machine learning model in Python using Google Colab.

## Dataset
- Source: Kaggle – Social Media vs Productivity
- File used: social_media_vs_productivity.csv
- Important columns (examples): daily_social_media_time,actual_productivity_score, social_platform_preference, number_of_notifications

## Technologies Used
- Python
- Google Colab
- Google Drive
- Libraries: pandas, matplotlib, scikit-learn

## What the Notebook Does
1. Mounts Google Drive and loads the dataset using pandas.
2. Checks dataset shape and missing values.
3. Cleans the data by dropping rows with missing key values.
4. Performs exploratory data analysis (EDA) using summary statistics and visualisations.
5. Builds a simple Linear Regression model to predict productivity from daily social media time.
6. Evaluates the model using MAE and R² score.
7. Prints a short summary of the findings.

## How to Run
1. Open the notebook SocialMediaVsProductivity.ipynb in Google Colab.
2. Mount Google Drive.
3. Upload the dataset CSV to a folder in Drive and update the file_path variable if required.
4. Run all cells from top to bottom.

## Student Details
- Name: Busani Naga Jahnavi
- USN: 25BAI10480
- Course: Python Essentials
- College: VIT Bhopal
