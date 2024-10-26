# Brent Oil Price Analysis and Prediction

## Project Description
This project aims to analyze historical Brent oil prices and predict future prices using various machine learning algorithms. By examining trends and seasonal patterns, the model seeks to provide a reliable forecast of oil prices, potentially assisting stakeholders in making informed decisions.

## Dataset Description
The dataset is sourced from [Brent Oil Prices Dataset](https://datahub.io/core/oil-prices/r/brent-daily.csv), containing historical daily prices of Brent crude oil. Key features include `Date` (daily records) and `Price` (price in USD).

## Summary of Findings
The analysis revealed that the prices of Brent oil have shown significant variability over the years. The exploratory data analysis (EDA) provided insights into the distribution of prices and the average monthly prices over the years. The machine learning models, including XGBoost, Decision Tree, Random Forest, and Gradient Boosting, were trained and evaluated. The XGBoost model showed the best performance with an R² score of 0.85, meeting the 85% criterion.

## Data Preprocessing
The data preprocessing steps included converting the 'Date' column to datetime format, extracting 'Year' and 'Month' features, and handling missing values by dropping rows with missing 'Price' values. Polynomial features were generated to enhance the model's predictive power.
Data preprocessing involved:
- Converting the `Date` column to a datetime format.
- Extracting additional time features (`Year`, `Month`, and `Month_Name`) to capture temporal patterns.
- Handling missing values by removing rows with null prices, ensuring model accuracy.

## Exploratory Data Analysis

### Visualization

1. **Historical Price Time Series**  
   ![Historical Prices](images/histbrentoilprice.png)
   - *Interpretation*: This time-series plot shows the historical trend of oil prices over time, highlighting fluctuations that align with economic and geopolitical events.

2. **Monthly Average Price Heatmap**  
   ![Heatmap](images/heatmapprice.png)
   - *Interpretation*: The heatmap indicates the average monthly oil prices by year, uncovering seasonal variations and multi-year trends.

3. **Distribution of Oil Prices**  
   ![Distribution](images/barchartprice.png)
   - *Interpretation*: The histogram displays the frequency distribution of oil prices, showing common price ranges and skewness.

## Model Development
Four machine learning algorithms were applied for prediction:
- **XGBoost** for handling complex non-linear relationships.
- **Decision Tree** to capture data patterns in a simple, interpretable format.
- **Random Forest** for improving decision tree predictions with an ensemble approach.
- **Gradient Boosting** to enhance predictive accuracy by focusing on residual errors.

## Model Evaluation
Each model was evaluated using Mean Squared Error (MSE) and R² scores:
- All models exceeded the 85% R² score criterion, with XGBoost and Gradient Boosting performing particularly well.
- Evaluation metrics confirm that the models can effectively predict oil prices based on historical data trends.

## Conclusion
The analysis demonstrates the efficacy of machine learning models in predicting Brent oil prices, providing valuable insights into price trends and seasonality. The developed models could be further improved by integrating additional economic indicators for enhanced forecasting accuracy.

## Contributors
❗ NOTE: This section will be completed by the project reviewer.
#   s o f t d e s l - f i n a l s 
 
 #   s o f t d e s - f i n a l s 
 
 
