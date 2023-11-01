# Machine Learning Project: Uber NYC 2022 Analysis (Course: Introduction to Data Analytics)

## Overview
This repository contains the code and dataset used for analyzing Uber rides in New York City in 2022. The analysis is performed using machine learning techniques to gain insights into Uber ride patterns and trends. The objective is to predict uber fares for driver i at trip t.

## Dataset
The dataset used for this analysis can be found in the `dataset` folder. The datasets ranging from 'fhvhv_tripdata_2022-01.parquet' to 'fhvhv_tripdata_2022-12.parquet' are concatenated to 'df_uber_2022.csv'. 'df_uber_2022.csv' contains Uber ride data for the year 2022 in New York City. Please refer to this dataset for the source of the information used in the analysis. Furthermore the datasets 'nyc_weather_data_2022.csv' and 'taxi_zone_lookup.csv' are used for feature engineering

## Code
The main code for the analysis is provided in the Jupyter Notebook `uber_code2.ipynb`. This notebook contains the Python code and explanations for the machine learning techniques used to analyze the Uber ride data. You can run the notebook in your local environment to explore the analysis and results.

## Dependencies
- Python 3.8
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Pyarrow
