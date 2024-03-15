# Yulu-Hypothesis-Testing
  - Yulu is India’s leading micro-mobility service provider, which offers unique vehicles for the daily commute. Starting off as a mission to eliminate traffic congestion in India, Yulu provides the safest commute solution through a user-friendly mobile app to enable shared, solo and sustainable commuting.
  - Strategically positioned Yulu zones span key locations such as metro stations, bus stands, residential areas, corporate offices, and commercial hubs.This network ensures seamless connectivity for commuters, making the first and last miles of their journey smooth, cost-effective, and hassle-free.

## Business Problem:
The company aims to address the following inquiries:

    - 1. Identification of Significant Variables: Determining the key variables that play a significant role in predicting the demand for shared electric cycles within the Indian market.
    - 2. Evaluation of Variable Efficacy: Assessing how well the identified variables collectively describe the fluctuations and patterns observed in electric cycle demand. 
## Dataset Information:
### Source:
Please check the dataset at: "https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/001/428/original/bike_sharing.csv?1642089089"

### Feature Information:
- datetime: datetime
- season: season (1: spring, 2: summer, 3: fall, 4: winter)
- holiday: whether day is a holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
- workingday: if day is neither weekend nor holiday is 1, otherwise is 0.
- weather:
    1: Clear, Few clouds, partly cloudy, partly cloudy
    2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
    3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
    4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
    temp: temperature in Celsius
- atemp: feeling temperature in Celsius
- humidity: humidity
- windspeed: wind speed
- casual: count of casual users
- registered: count of registered users
- count: count of total rental bikes including both casual and registered
