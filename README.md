# Wildfire Potential Prediction at Ignition

## Project Overview

Wildfires can begin under similar conditions but develop very differently, from small, contained fires to events that burn extensive areas. This project investigates whether information available around the time of ignition can help identify the potential for an extreme wildfire in New Zealand.

The aim is to explore historical wildfire records and the relationships between fire outcomes, weather, fuel characteristics, season, and location. The longer-term objective is to establish a data-driven basis for assessing extreme-fire potential early, when that information could be most useful for situational awareness and response planning.

## Exploratory Data Analysis (EDA)

The current notebook focuses on understanding the dataset and identifying patterns that may inform later predictive modelling:

- **Fire size and extreme events:** examines the distribution of burned area, including its long right tail, where a small number of fires account for very large burned areas. Log-transformed area is used in visualisations to make this skew easier to inspect.
- **Weather conditions:** explores relationships between fire size and variables such as the Fire Weather Index (FWI) and relative humidity (RH). These comparisons help assess whether weather indicators may be informative, while recognising that no single variable explains fire growth on its own.
- **Seasonality and geography:** analyses when and where fires are recorded, including monthly and spatial patterns.
- **Fuel characteristics:** examines the distribution of recorded fuel types as potential context for fire behaviour.
- **Data quality and historical coverage:** investigates missing values and how the availability of features changes over time, important considerations when selecting predictors and avoiding misleading comparisons across years.

## Current Findings and Status

The EDA highlights that wildfire burned area is highly skewed, with many small fires and a relatively small number of very large events. It also explores potential associations between fire size and weather, fuel, time, and location. These patterns help guide feature selection and the next stages of the project.

**Current stage: exploratory analysis.** The notebook and visualisations document dataset characteristics and candidate relationships. They should not be interpreted as proof of causation or as evidence of a validated operational prediction model. Model development, evaluation, and the reliability of predictions at ignition need to be assessed separately.
