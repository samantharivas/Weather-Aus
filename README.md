# Rainfall in Australia 
University of San Diego
Spring 2023 ADS502 Final Project

## Contributors

- Justin Farnan
- Samantha Rivas
- Jessica Hin

## Analysis Goals

The primary goal of this project is to analyze and identify the key weather features that influence the likelihood of rainfall in Australia. Specifically, the project aims to predict the probability of rain on the next day based on the current day's weather conditions. Additional objectives include identifying regions in Australia with the highest rainfall and exploring the relationships between different weather features.

## Methodology

1. **Data Preprocessing**
    - Cleaning and formatting the data
    - Handling missing values
    - Identifying and retaining significant outliers
    - Standardizing numeric fields

2. **Exploratory Data Analysis (EDA)**
    - Graphical relationships
    - Correlation matrices
    - Histograms, line plots, heatmaps, and boxplots

3. **Data Mining Techniques**
    - Naive Bayes Classification
    - Random Forests
    - Logistic Regression

4. **Model Evaluation**
    - Assessing model performance using accuracy scores, precision, recall, and f1-scores.

## Dataset Description

### Data Source

The dataset used for this project is an open dataset from Kaggle.com titled "Weather in AUS". It contains weather data for Australia from 2007 to 2017.

### Number of Variables

The dataset contains 24 features:

- **Date**: Date of observation
- **Location**: Province or territory in Australia
- **MaxTemp**: Highest temperature of the day (℃)
- **Rainfall**: Rainfall in millimeters
- **Evaporation**: Evaporation in millimeters
- **Sunshine**: Daily average number of bright sunshine hours
- **WindGustDir**: Wind gust direction
- **WindGustSpeed**: Wind gust speed in km/h
- **WindDir9am**: Wind direction at 9am
- **WindDir3pm**: Wind direction at 3pm
- **WindSpeed9am**: Wind speed in km/h at 9am
- **WindSpeed3pm**: Wind speed in km/h at 3pm
- **Humidity9am**: Humidity at 9am in %
- **Humidity3pm**: Humidity at 3pm in %
- **Pressure9am**: Pressure in millibars at 9am (mb)
- **Pressure3pm**: Pressure in millibars at 3pm (mb)
- **Cloud9am**: Cloud amount measured in Oktas
- **Cloud3pm**: Cloud amount measured in Oktas
- **Temp9am**: Temperature at 9am (℃)
- **Temp3pm**: Temperature at 3pm (℃)
- **RainToday**: Whether or not it rained today
- **RISK_MM**: Amount of rain, a measure of the 'risk'
- **RainTomorrow**: Whether or not it rained tomorrow

### Dataset Size

The dataset contains records from 2007 to 2017, with a total of approximately 142,193 entries.

## Repository Contents

- **weatherAUS.csv**: Original dataset from Kaggle.
- **Weather AUS.ipynb**: Jupyter notebook containing data cleaning, preprocessing, EDA, modeling, and evaluation.
- **README.md**: This README file providing an overview of the project.

## Prerequisites

- Python 3.8+
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, nltk, imbalanced-learn

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/username/rainfall-in-australia.git
    ```

2. Navigate to the project directory:
    ```bash
    cd rainfall-in-australia
    ```
3. Open the Jupyter Notebooks to explore the analysis and modeling:
    ```bash
    jupyter notebook Weather AUS.ipynb
    ```

## License

This project is licensed under the MIT License - see the LICENSE file for details.
