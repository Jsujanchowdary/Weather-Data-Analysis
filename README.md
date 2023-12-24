# Weather-Data-Analysis
basic data analytics and visualization on the Weather Data
Set to gain insights.
## Dataset:
The Dataframe ‘df’ has 366 entries (rows) and 22 columns. The columns are:
1.	MinTemp: Minimum temperature (float64)
2.	MaxTemp: Maximum temperature (float64)
3.	Rainfall: Amount of rainfall (float64)
4.	Evaporation: Amount of evaporation (float64)
5.	Sunshine: Amount of sunshine (float64, 3 missing values)
6.	WindGustDir: Wind gust direction (object, 3 missing values)
7.	WindGustSpeed: Wind gust speed (float64, 2 missing values)
8.	WindDir9am: Wind direction at 9am (object, 31 missing values)
9.	WindDir3pm: Wind direction at 3pm (object, 1 missing value)
10.	WindSpeed9am: Wind speed at 9am (float64, 7 missing values)
11.	WindSpeed3pm: Wind speed at 3pm (int64)
12.	Humidity9am: Humidity at 9am (int64)
13.	Humidity3pm: Humidity at 3pm (int64)
14.	Pressure9am: Atmospheric pressure at 9am (float64)
15.	Pressure3pm: Atmospheric pressure at 3pm (float64)
16.	Cloud9am: Cloudiness at 9am (int64)
17.	Cloud3pm: Cloudiness at 3pm (int64)
18.	Temp9am: Temperature at 9am (float64)
19.	Temp3pm: Temperature at 3pm (float64)
20.	RainToday: Whether it rained today (object)
21.	RISK_MM: Risk in mm (float64)
22.	RainTomorrow: Whether it will rain tomorrow (object)
There are some missing values in the columns Sunshine, WindGustDir, WindGustSpeed, WindDir9am, WindDir3pm, and WindSpeed9am. The data types are float64, int64, and object (likely string).

## Descriptive Statistics:
- Compute and present basic statistics (mean, median, standard deviation) for MinTemp, MaxTemp, Rainfall, and Evaporation.

  ![image](https://github.com/Jsujanchowdary/Weather-Data-Analysis/assets/91127394/31559ba6-f1f5-43c9-9f5c-1b650f858581)

  ![image](https://github.com/Jsujanchowdary/Weather-Data-Analysis/assets/91127394/b75469b1-e2de-4d35-a6d5-50bb5f42ca47)

## Time Series Visualization:
- Create a line chart to show the variations in weather variables over time, identifying trends or patterns.
  ![image](https://github.com/Jsujanchowdary/Weather-Data-Analysis/assets/91127394/13585b8c-e7d4-49a6-b336-39472eb94472)

  ![image](https://github.com/Jsujanchowdary/Weather-Data-Analysis/assets/91127394/9ff06e44-3ce0-4055-877b-0cabeb0c6d2b)


  ![image](https://github.com/Jsujanchowdary/Weather-Data-Analysis/assets/91127394/34df9dea-bfba-4e35-ba1c-94625c2f3e94)

## Correlation Analysis:
- Calculate and visualize correlations between MinTemp, MaxTemp, Rainfall, and Evaporation using a heatmap.

  ![image](https://github.com/Jsujanchowdary/Weather-Data-Analysis/assets/91127394/b14415b0-3401-4e03-9e75-4c7e8259e4ef)

## Rainfall Distribution:
- Illustrate the distribution of rainfall through a histogram or kernel density plot, highlighting common levels and outliers.

  ![image](https://github.com/Jsujanchowdary/Weather-Data-Analysis/assets/91127394/cc17ca34-859e-467d-9f91-7653735651bf)

## Seasonal Analysis:
- Analyze average values of weather variables across different seasons and visualize seasonal patterns with bar graphs.

  ![image](https://github.com/Jsujanchowdary/Weather-Data-Analysis/assets/91127394/fdc09d96-749c-4962-a05c-3578cc890cce)

  ![image](https://github.com/Jsujanchowdary/Weather-Data-Analysis/assets/91127394/2ce54dd4-f3b4-46c4-a861-546c80eb6181)

