# Bitcoin Price Prediction Using Machine Learning Models

## Project Overview
This project aimed to predict Bitcoin price movements using various machine learning models and time series analysis techniques. The study covered data from November 19, 2015, to November 19, 2020, providing insights into the challenges and potential approaches for cryptocurrency price prediction.

## Key Findings
1. **Model Performance**: Logistic Regression and Random Forest models achieved modest accuracy (~55%) in predicting price directions, with better performance in predicting price increases than decreases.

2. **Time Series Analysis**: ARIMA model (2,1,0) showed reasonable performance with a mean squared error of 2.394227%, capturing overall trends but struggling with sudden price movements.

3. **Data Characteristics**: Bitcoin price data exhibited high volatility and non-stationarity, requiring logarithmic transformation and differencing for effective analysis.

4. **Feature Importance**: Technical indicators and moving averages played crucial roles in model performance, as evidenced by correlation analysis.

## Tools and Techniques
- **Programming Language**: Python
- **Data Analysis Libraries**: Pandas, NumPy
- **Machine Learning Libraries**: Scikit-learn
- **Time Series Analysis**: Statsmodels (for ARIMA modeling)
- **Data Visualization**: Matplotlib, Seaborn
- **Statistical Tests**: Augmented Dickey-Fuller (ADF) test for stationarity
- **Feature Engineering**: 
  - Simple Moving Averages (SMA)
  - Bollinger Bands
  - Moving Average Convergence Divergence (MACD)
- **Models Implemented**:
  - Logistic Regression
  - Random Forest Classifier
  - ARIMA (AutoRegressive Integrated Moving Average)
- **Model Evaluation Metrics**: 
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-score)
  - Root Mean Square Error (RMSE)
  - Mean Squared Error (MSE)

## Challenges and Limitations
- High volatility and unpredictability of cryptocurrency markets
- Limited ability to capture external factors influencing prices
- Need for continuous model updating due to rapidly changing market dynamics

## Future Work
- Explore ensemble models and deep learning techniques
- Incorporate additional data sources (e.g., sentiment analysis, economic indicators)
- Implement real-time model updating and prediction mechanisms

## Conclusion
This project demonstrates the complexities involved in predicting Bitcoin prices and highlights the potential of machine learning and time series analysis in understanding cryptocurrency market trends. While perfect prediction remains elusive, the models and techniques explored provide valuable insights for investors and researchers in the rapidly evolving field of cryptocurrency analysis.

## Why This Project?
I undertook this project to deepen my understanding of both cryptocurrency markets and advanced data analysis techniques. By applying machine learning and time series analysis to Bitcoin price data, I aimed to:

1. Gain practical experience in handling and analyzing financial time series data
2. Explore the challenges of predicting highly volatile assets
3. Develop skills in implementing and evaluating various machine learning models
4. Contribute to the growing body of research on cryptocurrency price prediction

Through this project, I've not only enhanced my technical skills but also gained valuable insights into the complexities of financial markets and the potential applications of data science in this domain.
