
## **Macroeconomics Analytics**
## **Overview**
This project focuses on analyzing macroeconomic data, specifically GDP, unemployment rates, and inflation. I used publicly available data from the World Bank to perform exploratory data analysis (EDA), simulation, and machine learning tasks to gain insights into economic trends.

Real dataset from Data World Bank!

## **Data Pre-processing**
- The initial data cleaning and transformation involved the following steps:
- Cleaning: Removed irrelevant columns, handled NaN values, and merged data from different sources into a unified dataset.
- Data Conversion: Converted values into more readable formats, ensuring consistency across all datasets.- Reshaping Data: Used melting to transform dataframes from wide format to long format for easier analysis.
- Merging Data: Consolidated all individual datasets (GDP, unemployment, inflation) into a single, easy-to-access dataframe for further analysis.

## **Exploratory Data Analysis (EDA)**
- Analyzed the relationship between unemployment and inflation in Canada and Italy, exploring the trade-off and historical trends.
- Used the Monte Carlo method to simulate and predict GDP growth, factoring in randomness to model future economic scenarios.
- Applied a Random Forest Classifier to predict years of economic recession based on historical data of GDP, unemployment, and inflation.
  - 44% of accuracy, it could be higher with a larger dataset.

## **Key Insights**
- The analysis of the Phillips Curve in Canada and Italy revealed the historical trade-off between unemployment and inflation, helping to understand how these two macroeconomic indicators interact over time.
- The Monte Carlo simulation demonstrated the potential future scenarios of GDP growth, incorporating randomness in economic forecasting..
- Recession Prediction: The application of the Random Forest Classifier allowed for the identification of years of economic recession, based on historical data of GDP, unemployment, and inflation. This model can potentially be used to predict future recessions by analyzing similar economic patterns.

## **Technologies Used**
  - **Python**, **Pandas**, **Matplotlib**, **Numpy**, **Scikit-learn**.

## **Conclusions**
This project provided valuable insights into macroeconomic trends, utilizing tools like Python for data preprocessing, exploratory analysis, and machine learning techniques. Additionally, the Random Forest model provided a data-driven approach to predicting economic recessions, demonstrating the potential of machine learning in economic forecasting.
