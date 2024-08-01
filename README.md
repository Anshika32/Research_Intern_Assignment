# Heart Rate and Sleep Data Analysis

## Project Overview

This project aims to analyze heart rate and sleep data to detect anomalies and evaluate sleep quality. The analysis includes advanced techniques such as time series decomposition and anomaly detection using Isolation Forest.

## Data Files

- **heartrate.csv**: Contains one month of heart rate data with timestamps.
- **sleep.csv**: Contains sleep data with timestamps, minutes asleep, and sleep type.
- **steps.csv**: Contains steps data with timestamps.

## Requirements

- Python 3.x
- Pandas
- Matplotlib
- Scikit-learn
- Statsmodels

You can install the required packages using the following command:

```bash
pip install pandas matplotlib scikit-learn statsmodels
```

## Analysis Steps

### Heart Rate Anomaly Detection

1. **Load and Preprocess Data**: Load the heart rate data, convert the datetime column to a proper format, and handle missing values.
2. **Time Series Decomposition**: Decompose the time series data to understand the trend, seasonality, and residual components.
3. **Anomaly Detection using Isolation Forest**: Detect anomalies using the Isolation Forest algorithm.
4. **Visualize Anomalies**: Plot the data along with the detected anomalies for visualization.

### Sleep Data Analysis

1. **Load and Preprocess Data**: Load the sleep and steps data, convert the datetime columns to a proper format.
2. **Sleep Interruption Analysis**: Analyze sleep interruptions by identifying periods marked as 'wake' in the sleep data.
3. **Walking Events During Night**: Identify walking events during the night using the steps data.
4. **Sleep Quality Assessment**: Evaluate sleep quality based on the duration and type of sleep.
5. **Health Implications**: Discuss the possible reasons for sleep interruptions and their health implications.

## Results

The analysis results include:

- Decomposition plots of the heart rate data showing trend, seasonality, and residual components.
- Anomalies in heart rate data visualized using scatter plots.
- Analysis of sleep interruptions and walking events during the night.
- Assessment of sleep quality and discussion on health implications.
