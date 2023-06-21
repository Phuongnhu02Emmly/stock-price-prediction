# stock-price-prediction
# Comparative test of the application of Technical Analysis, Machine learning and Deep learning to stock price prediction
## Introduce:
In this topic, various models will be used to forecast the Adjusted Closing price for VIC Group's stock price data. From simple technical analysis indicators (such as Moving Averages – Moving Average), Linear Regression algorithms, machine learning models from simple (k-Nearest Neighbor) to more complex (Prophet), and finally deep learning algorithms (LSTM - Long Short-Term Memory). The methods will be applied in turn and compare the results to find out which model gives the most optimal performance.
## Data
Dữ liệu trong bài làm là dữ liệu giá đóng cửa điều chỉnh của Tập đoàn VIC, với interval cho mỗi điểm dữ liệu là 1 ngày, được lấy trong giai đoạn từ ngày 08/07/2013 đến ngày 14/6/2023 (là thời điểm mới nhất). Dữ liệu được lấy trực tiếp từ trang Investment.com. 
## VISUALIZATION
## Moving Average
A moving average is a simple technical analysis indicator whereby the next observation is the average of all past observations creating a continuously updated average price.
## Linear Regression
This model adopts a linear approach to model the relationship between the dependent variable and the independent variable(s), and is also the simplest form of machine learning.
## k-Nearest Neighborhood
Based on the independent variables, k-Nearest Neighbors finds similarity between new and old data points and assumes that similar data points exist in close proximity. It chooses k for the nearest “neighbors” and then based on these “neighbors” predicts a value for the new observation. k-Nearest Neighborhood is known as a simple machine learning model.
## Prophet
Next, we will use an analytic and predictive model of the time series data that takes into account both the trend and the seasonality of the data set. Prophet is an additive model-based time-series data forecasting package where non-linear trends are consistent with annual, weekly, and daily seasonality, plus external influences such as special occasions.
## Long Short Term Memory (LSTM)
LSTM is a Recurrent Neural Network that can store important information in the past and forget about unimportant information. It uses short-term memory processes to create longer-term memory and introduces the concept of gateways to control the flow of information in the network by having input, output, and forget gate mechanisms.
