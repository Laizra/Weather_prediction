# Weather data analysis and prediction
![Weather Forescasting](Weather_forecasting_Readme_Image.png)

To view the process, please open the [main.ipynb](https://github.com/Laizra/Weather_prediction/blob/main/main.ipynb) file.
## Description

This project aims to predict daily temperature highs and lows for nine major cities using machine learning, specifically Ridge regression and statistical analysis techniques. It leverages historical weather data to uncover patterns and factors influencing temperature changes, providing localized forecasts that are essential for various applications, such as agriculture and disaster preparedness.

The main features of the project include:

* **Temperature Prediction**: Uses historical weather data to predict future daily temperature highs and lows.
* **Data Analysis**: Analyzes patterns and trends in weather data to uncover key influencing factors.
* **Visualization**: Provides visual outputs showing predicted vs. actual temperature readings for better understanding and interpretation.

## Dependencies
* Python 3.10.12
* ipykernel 6.29.5 (optional)
* pandas 2.2.2
* matplotlib 3.9.2
* seaborn 0.13.2
* statsmodels 0.14.2
* scikit-learn 1.5.1

> [!NOTE]
> Ensure to use the specified library versions for compatibility. Users may need to create a virtual environment to avoid conflicts with other packages.

## Data used

**Data Dictionary**:
For the dataset we collected weather data of 9 random major cities of the world; Beijing, Berlin, London, Mexico City, Moscow, Ottawa, Paris, Rome, and Washington DC.

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

#### Notes:

- **Temperature and Dew Point**: Measured in degrees Celsius (°C).
- **Precipitation and Snow**: Precipitation is measured in millimeters (mm), and snow depth is measured in centimeters (cm).
- **Wind Speed and Gusts**: Measured in kilometers per hour (km/h).
- **Visibility**: Measured in kilometers (km).
- **Atmospheric Pressure**: Measured in millibars (mb).
- **Sunrise and Sunset**: Represent times of sunrise and sunset, typically in a time format (HH:MM).
- **Moonphase, Conditions, Description, Icon, and Stations**: These are categorical or descriptive fields that provide context to the weather data but do not have numerical values.

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
