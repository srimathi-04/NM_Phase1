# Naan Mudhalvan Project

## COVID-19 Vaccination Analysis

## Introduction

This project focuses on analyzing the COVID-19 vaccination progress across different countries. The analysis is performed using various machine learning algorithms to predict the total number of vaccinations based on different features related to the vaccination process.

## Project Structure

The project is organized as follows:

- `data` ADS_Phase_2/Dataset: Contains the dataset used for analysis.
- `notebooks`ADS_Phase_5 : Contains Jupyter notebooks for different phases of the project.
- `requirements.txt`: File specifying the necessary packages and their versions.
- `README.md`: This file, providing an overview of the project.

## Dataset

The dataset used in this project contains the following features:

- country
- iso_code
- date
- total_vaccinations
- people_vaccinated
- people_fully_vaccinated
- daily_vaccinations_raw
- daily_vaccinations
- total_vaccinations_per_hundred
- people_vaccinated_per_hundred
- people_fully_vaccinated_per_hundred
- daily_vaccinations_per_million
- vaccines
- source_name
- source_website

## Data Preprocessing

The data preprocessing steps include handling missing values, label encoding categorical features, and scaling the data for model training. Data process is done by `ADS_Phase_3`

## Analysis Techniques

The analysis includes the use of various supervised and unsupervised learning algorithms such as Linear Regression, Polynomial Regression, Decision Trees, and XGBoost. Additionally, it utilizes K-means clustering for unsupervised learning.

## Results

The project provides insights into the relationship between different vaccination features and the total number of vaccinations. It also offers predictions for the total vaccinations based on the trained machine learning models.

## Requirements

The project requires the installation of specific Python packages specified in the `requirements.txt` file. Use the following command to install the necessary packages:

```bash
pip install -r requirements.txt
```

## Usage

The Jupyter notebooks in the `Final Analysis.ipynb` folder provide detailed steps for data analysis, preprocessing, and model training. Follow the instructions in the notebooks to understand the analysis process.

## Author

[Siva Ramana H V](https://sivaramana.tech)

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
---
