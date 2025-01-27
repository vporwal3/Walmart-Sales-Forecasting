# Walmart-Sales-Forecasting
![image](https://user-images.githubusercontent.com/98642342/211175495-ca088645-32e7-4bae-9f74-20babbd65a2d.png)

In a world running on generating and analyzing data, harnessing and utilizing it to create effective marketing strategies is extremely essential for organizations. For an establishment as big as Walmart, it is necessary to organize and analyze the large volumes of data generated to make sense of existing performance and identify growth potential. The main goal of this project is to understand how different factors affect the sales for Walmart and how these findings could be used to create more efficient plans and strategies directed at increasing revenue.

Time series data often arise when monitoring industrial processes or tracking corporate business metrics. The analysis of time series accounts for the fact that data points taken over time may have an internal structure (such as autocorrelation, trend or seasonal variation) that should be accounted for.

This report explores the performance of a subset of Walmart stores and forecasts future weekly sales for these stores based on several models including Ridge Regression, Random Forest, XGBoost, SARIMA and LSTM model. An exploratory data analysis has also been performed on the dataset to explore the effects of different factors like holidays, fuel price, and temperature on Walmart’s weekly sales which provides an overview of the overall predicted sales.

Through the analysis, it was observed that the SARIMA model provided the most accurate sales predictions. Relationships were observed between factors like store size, holidays, unemployment, and weekly sales. Through the implementation of interaction effects, as part of the linear models, the relationship between a combination of variables like temperature, CPI, and unemployment was observed and had a direct impact on the sales for Walmart stores.

For this project, we used the “Walmart Sales Forecasting” Kaggle competition as our benchmark reference. The competition was posted 9 years ago and has over 688 participants. The competition is evaluated on a weighted mean absolute error (WMAE) as shown in the image below. Since the sales are higher during the holidays which constitutes only a very small fraction of the year, they are assigned higher weights. This contributes towards giving more weightage to the prediction of Sales during the holidays as opposed to off-seasonal sales.

<img width="542" alt="Screenshot 2023-01-07 at 7 43 16 PM" src="https://user-images.githubusercontent.com/98642342/211175575-a548e60d-4307-43a0-a2f3-b25fe713fe15.png">
