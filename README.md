### Feature Scaling 

# Why Feature Scaling Required ?
- It's a technique for independent features those are carrying different magnitude, range and units. In order to convert those into a same scale we need feature scaling.
- Some of the Distance based Algorithms and Gradient Descent based Algorithms, we need to do Feature Scaling. Why in the sence, it allows Algorithms to learn better parrterns.
- Algorithms like tree based, we don't need feature scaling.Beacuse these are conditional based Algorithms.Based on some codition it gonna make a tree in order to predict the future.
- 3 different scalers in the Scikit-learn library for feature scaling and they are:
1. MinMaxScaler
 
https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.MinMaxScaler.html

2. StandardScaler
 
https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html

3. RobustScaler
 
https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.RobustScaler.html

# MinMaxScaler

![images (1)](https://user-images.githubusercontent.com/84494071/132119080-e3dd92d2-20ad-478b-b2b7-d41b88697879.png)

- MinMaxScaler is a scaling technique which used in Deep learning mostly.
- It convert all data points into same scale which ranges between 0 to 1 by using above equation.

# Standardisation

![1_M3fNcpf2mjpeVsersdQMYA](https://user-images.githubusercontent.com/84494071/132119930-f06cd052-d423-42b3-a07b-1cc9e3788763.png)

- Standardisation or z score normalization is another scaling techniques where the values are centered around the mean with a unit standard diviation.

# Robust Scaler
Robust Scaler are robust to outliers.It is used to scale the feature to median and quantiles Scaling using median and quantiles consists of substracting the median to all the observations, and then dividing by the interquantile difference. The interquantile difference is the difference between the 75th and 25th quantile:

IQR = 75th quantile - 25th quantile

X_scaled = (X - X.median) / IQR

![Selerity-Robust-scaler](https://user-images.githubusercontent.com/84494071/132119761-e0f78143-8107-43bf-abac-ea6f6f27202c.png)

# Implementation with python:

Click here:-  https://github.com/Jyotiranjan404/Types-Of-Feature-Transformation/blob/main/Scaling%20Techniques.ipynb

