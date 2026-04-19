# Population Prediction in Bristol Using Historical Data
## Bristol Population Prediction Project (2011-2026)

## Project Overview

This project aims to predict Bristol’s population for 2025 and 2026 using historical demographic data from 2011 to 2024. The dataset includes key variables such as population, births, deaths, natural change, and migration.

The notebook follows a simple data science workflow, loading and preparing the data, exploring trends through visualisation, creating useful features, training multiple machine learning models, comparing their performance, and selecting the best model for forecasting.

The main goal of this project is to understand population patterns in Bristol and use machine learning to produce future population estimates in a clear and practical way.

## Objectives

* To analyse historical population data for Bristol (2011–2024)
* To clean and prepare the dataset for analysis
* To explore population trends using visualisation
* To create useful features such as lagged population values
* To apply different machine learning models for prediction
* To compare model performance using evaluation metrics (MAE, RMSE, R²)
* To select the best model
* To predict Bristol’s population for 2025 and 2026

Here is a **better version including ONS** (simple and report-ready):

---

## **Dataset and Data Integration**

This project uses population data from the Office for National Statistics (ONS). The dataset covers Bristol from 2011 to 2024 and includes variables such as population, births, deaths, natural change, and migration.

The data was originally in a wide format, where each year was stored in separate columns. It was then converted into a tidy format, where each row represents one year. This makes the data easier to analyse and use in machine learning models.

Data integration involved selecting only the Bristol data from the full dataset and combining all relevant variables into one table. This final dataset was then used for analysis and prediction.


