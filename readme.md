# Autoregressive and Moving Average Time Series Model for IOT Sensor Data 

## Overview

We will study time series analysis, focusing specifically on forecasting sensor data. Sensor data plays a crucial role in various fields, including IoT, environmental monitoring, manufacturing, and more. Accurately predicting future sensor readings is essential for proactive decision-making and optimizing system performance.

---

### Project Objectives

- Gain a solid understanding of time series analysis.
- Explore different types of time series data, including continuous and discrete.
- Understand the components of time series, such as trend, seasonality, and irregularity.
- Learn the concept of stationarity and how to test for it using statistical tests like ADF and KPSS.
- Utilize autocorrelation and partial autocorrelation functions (ACF and PACF) to identify dependencies and correlations in sensor data.
- Develop and apply moving average (MA) and autoregressive (AR) models for forecasting sensor data.
- Evaluate model performance using metrics like Root Mean Squared Error (RMSE).

---

## Data Description

The dataset used in this project consists of IoT sensor data from a chiller. It contains the following columns:

- **Time**: Timestamp of the sensor reading.
- **IOT_Sensor_Reading**: Reading obtained from the primary sensor.
- **Error_Present**: Indicates the presence of an error during the reading.
- **Sensor 2**: Reading obtained from a subordinate sensor.
- **Sensor_Value**: The final value to be predicted.

---

## Tech Stack

- **Language**: `Python`
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `scipy.stats`, `statsmodels`, `seaborn`

---

## Approach

1. Read the data.
2. Preprocess the data.
3. Perform Exploratory Data Analysis (EDA).
4. Check for stationarity in the data.
5. Analyze ACF and PACF plots.
6. Build the following models:
   - Moving Average (MA).
   - First-order autoregressive (AR).
   - Second/general order autoregressive (AR).
   - Third-order autoregressive (AR).
   - Fourth-order autoregressive (AR).
7. Evaluate the models' performance.

---

## Project Structure

- **input**: Contains the input data file "Data-Chillers.csv."
- **lib**: Contains reference materials and a Jupyter Notebook workbook for the project.
- **output**: Intended to store any project results or output files.
- **Readme.md**: This file, providing instructions and explanations about the project.
- **requirements.txt**: Specifies required dependencies.
- **src**: Contains the source code files, including the main engine file and modules for the machine learning pipeline.

---

## Key Concepts Explored

- Understanding the importance of time series analysis.
- Knowledge of different types of time series data.
- Awareness of the components of a time series.
- Ability to assess stationarity in time series data.
- Interpretation of ACF and PACF plots for modeling.
- Building MA and AR models.
- Hands-on experience in preprocessing time series data.
- Exploratory Data Analysis skills.
- Evaluating model performance using RMSE.

---

# Time Series

Time series is a sequence of information which attaches a time period to each value.
The value can be pretty much anything measurable.
It depends on time in some way, like prices, humidity or number of people.
As long as the values we record are unambiguous, any medium could be measured with Time series.
There aren't any limitations regarding the total time span of our Time series.
It could be a minute, a day, a month or even a century.
All we need is a starting and an ending point.


---



