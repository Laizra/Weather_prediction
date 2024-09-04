# Weather data analysis and prediction
![Weather Forescasting](Weather_forecasting_Readme_Image.png)

![Static Badge](https://img.shields.io/badge/StatisticalAnalysis-blue)
![Static Badge](https://img.shields.io/badge/MachineLearning-purple)
![Static Badge](https://img.shields.io/badge/Visualizations-yellow)
![Static Badge](https://img.shields.io/badge/DataScience-black)


### Check out thre process in the [main.ipynb](https://github.com/Laizra/Weather_prediction/blob/main/main.ipynb) file.

## Description

This project aims to predict daily temperature highs and lows for nine major cities using machine learning, specifically Ridge regression and statistical analysis techniques. It leverages historical weather data to uncover patterns and factors influencing temperature changes, providing localized forecasts that are essential for various applications, such as agriculture and disaster preparedness.

The main features of the project include:

* **Temperature Prediction**: Uses historical weather data to predict future daily temperature highs and lows.
* **Data Analysis**: Analyzes patterns and trends in weather data to uncover key influencing factors.
* **Visualization**: Provides visual outputs showing predicted vs. actual temperature readings for better understanding and interpretation.

## Dependencies
* Python 3.10.12
* ipykernel 6.29.5
* pandas 2.2.2
* matplotlib 3.9.2
* seaborn 0.13.2
* statsmodels 0.14.2
* scikit-learn 1.5.1

> [!NOTE]
> Users may need to create a virtual environment to avoid conflicts with other packages.

## Data Collection Overview
The dataset contains weather data collected from nine major cities globally: Beijing, Berlin, London, Mexico City, Moscow, Ottawa, Paris, Rome, and Washington DC. This diverse selection provides insights into various climatic conditions across different regions.

**Data Dictionary**
The following table outlines the columns in the dataset, providing descriptions and units for each variable:

| Column Name       | Description                                           | Unit            |
|-------------------|-------------------------------------------------------|-----------------|
| tempmax           | Maximum temperature recorded                          | °C              |
| tempmin           | Minimum temperature recorded                          | °C              |
| temp              | Mean temperature                                      | °C              |
| feelslikemax      | Maximum "feels like" temperature recorded             | °C              |
| feelslikemin      | Minimum "feels like" temperature recorded             | °C              |
| feelslike         | "Feels like" temperature                              | °C              |
| dew               | Dew point                                             | °C              |
| humidity          | Relative humidity                                     | %               |
| precip            | Precipitation amount                                  | mm              |
| precipprob        | Probability of precipitation                          | %               |
| precipcover       | Percentage of area covered by precipitation           | %               |
| snow              | Snowfall amount                                       | cm              |
| snowdepth         | Depth of snow on the ground                           | cm              |
| windgust          | Wind gust speed                                       | km/h            |
| windspeed         | Average wind speed                                    | km/h            |
| winddir           | Wind direction                                        | degrees         |
| sealevelpressure  | Atmospheric pressure at sea level                     | mb              |
| cloudcover        | Percentage of sky covered by clouds                   | %               |
| visibility        | Visibility distance                                   | km              |
| sunrise           | Time of sunrise                                       | Time            |
| sunset            | Time of sunset                                        | Time            |
| moonphase         | Phase of the moon                                     | -               |
| conditions        | General weather conditions (e.g., Rain, Clear)        | -               |
| description       | Text description of weather conditions                | -               |
| icon              | Weather icon representing conditions                  | -               |
| stations          | Identifiers of weather stations that provided data    | -               |

* Source: https://www.visualcrossing.com/weather-data
* Dataset: "Weather_data_2023_2024.csv"

## Usage instructions
1. Clone the repository:
```
git clone https://github.com/Laizra/Weather_prediction.git
cd Weather_prediction
```
2. Create a virtual environment and activate it:
```
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```
3. Install the required dependencies:
```
pip install -r requirements.txt
```

## Roadmap
This project is complete with no expected changes.

## Contact
Sofia G.
