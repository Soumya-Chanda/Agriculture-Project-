# Climate Trends and Crop Yield Prediction

A data-driven analysis of climate change and its impact on agricultural productivity using statistical modeling and predictive analytics.

## Overview

Climate change has become a major challenge for global agriculture, affecting crop productivity through rising temperatures, changing rainfall patterns, declining soil moisture, and increasing extreme weather events. Understanding these relationships is essential for improving agricultural planning and ensuring food security.

This project analyzes historical climate data from 2000–2024 to investigate how environmental factors influence crop yield. Using exploratory data analysis, correlation analysis, hypothesis testing, and multiple linear regression, the study identifies key climatic drivers of agricultural productivity and develops a predictive model for crop yield estimation.

## Objectives

- Analyze long-term trends in climate variables and crop yield.
- Examine relationships between climatic factors and agricultural productivity.
- Identify the most influential environmental variables affecting crop yield.
- Develop a predictive model for crop yield estimation.
- Generate insights to support climate-resilient agricultural practices.

## Dataset

The dataset contains annual observations from 2000 to 2024 with the following variables:

- Year
- Average Temperature (°C)
- Annual Rainfall (mm)
- Extreme Weather Events
- Soil Moisture (%)
- Crop Yield (tons/hectare)

## Methodology

### Data Preprocessing
- Data cleaning and validation
- Missing value checks
- Trend analysis
- Variable standardization

### Exploratory Data Analysis
- Temperature trend analysis
- Rainfall trend analysis
- Soil moisture trend analysis
- Crop yield trend analysis
- Extreme weather event analysis

### Statistical Analysis
- Correlation analysis
- ANOVA hypothesis testing
- Feature significance evaluation

### Predictive Modeling
- Multiple Linear Regression
- Model evaluation using R² and Adjusted R²
- Residual analysis
- Prediction performance assessment

## Key Findings

- Average temperature shows a strong negative relationship with crop yield.
- Soil moisture exhibits a strong positive relationship with agricultural productivity.
- Rainfall significantly contributes to crop growth and yield stability.
- Increasing extreme weather events negatively affect crop production.
- Climate variables collectively explain a substantial portion of crop yield variation.

## Results

The Multiple Linear Regression model achieved excellent predictive performance with a very high coefficient of determination, indicating a strong relationship between climatic variables and crop yield.

Major observations include:

- Rising temperatures are associated with declining crop productivity.
- Reduced soil moisture negatively impacts agricultural output.
- Rainfall remains a critical factor for sustaining crop yields.
- Climate change indicators demonstrate measurable effects on long-term agricultural performance.

## Technologies Used

- R
- ggplot2
- corrplot
- ggcorrplot
- readr
- tidyr

## Applications

- Agricultural Forecasting
- Crop Yield Prediction
- Climate Impact Assessment
- Food Security Planning
- Agricultural Policy Development
- Precision Agriculture

## Future Improvements

- Incorporate larger regional datasets.
- Develop machine learning models such as Random Forest and XGBoost.
- Implement time-series forecasting approaches.
- Integrate satellite and weather API data.
- Build an interactive dashboard for real-time crop yield prediction.

## Conclusion

This project demonstrates how statistical analysis and predictive modeling can be used to understand the impact of climate change on agricultural productivity. The findings highlight the importance of temperature, rainfall, and soil moisture in determining crop yield and provide a foundation for data-driven agricultural decision-making and climate-resilient farming strategies.
