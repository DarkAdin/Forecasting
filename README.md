# Forecasting
A forecasting algorithm for the Rohlik Orders challenge in Kaggle: https://www.kaggle.com/competitions/rohlik-orders-forecasting-challenge

This notebook implements four different approaches to performing forecasting predictions on the number of orders in the next 61 days following the dates from the training set. The three approaches are, in order:

1. **Prophet**: https://github.com/facebook/prophet
2. **Fitting polynomials**: https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.PolynomialFeatures.html
3. **SKForecast**: https://github.com/JoaquinAmatRodrigo/skforecast
4. **StatsForecast**: https://github.com/Nixtla/statsforecast

Reference each of the tools for their particular settings and hacking. The main idea is to infer a function that continues as part of a known, probably oscillatory function in time.

## Prophet

![](prague2_prophet.png "Prague_2 with Prophet")

## Fitting polinomials

![](prague2_poly.png "Prague_2 with a fitted polynomial")

## SKForecast

![](prague2_skforecast.png "Prague_2 with SKForecast")

## StatsForecast

![](prague2_statsforecast.png "Prague_2 with StatsForecast")
