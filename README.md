# Hotel-Cancellation-Prediction

## About
This is a mini-project for SC1015 (Introduction to Data Science and Artificial Intelligence).


1. [Data Preparation and Cleaning, Data Analysis and Visualization Part 1](https://github.com/Duyi00/Hotel-Cancellation-Prediction/blob/main/1015%20(Data%20Preparation%20and%20Cleaning%2C%20Data%20Analysis%20and%20Visualisation%20Part%201).ipynb)
2. [Data Analysis and Visualization Part 2, Machine Learning](https://github.com/Duyi00/Hotel-Cancellation-Prediction/blob/main/1015%20(Data%20Analysis%20and%20Visualisation%20Part%202%2C%20Machine%20Learning).ipynb)


## Contributors

- @Duyi00 Data Preparation and Cleaning, Data Visualization
- @zihan15 Machine Learning
- @pebblepaw Data Preparation and Cleaning, Data Visualization


## Problem Definition

- Predict whether a hotel reservation will be cancelled based on variables [to be determined]
- Which is the best prediction model

## Models Used

- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boost Classifier
- Ada Boost Classifier
- Cat Boost Classifier
- XGBoost Classifier
- Logistic regression

## Conclusion

- Random Forest Model is able to predict whether a reservation will be cancelled with 85% accuracy and low false positive rate (8%)
- Random Forest is the most accurate out of all the models used
- Longer lead time and higher adr equates to higher chance of cancellation
- Deposit type affects cancellation rate significantly

## Recommendations

- Lead time : Allow reservations up to 200 days in advance, chance of cancellation increases linearly from there to 400 days. 
- Day/Month : Thursday - Saturday especially during April - October have higher cancellation rates. Allow for more over-booking during this period.

## What did we learn from this project?

- Using plotly express to create interactive visualisation
- Plotted geographical data with plotly chloropleth
- Implemented one hot encoding for categorical data and time series
- Implementing 5 new Machine Learning models for prediction 
- Collaborating using GitHub

## References
- <https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand>
- <https://www.datacamp.com/community/tutorials/understanding-logistic-regression-python>
- <https://blog.experience-hotel.com/where-do-cancellations-come-from/#:~:text=Average%20cancellation%20rates&text=The%20average%20percentage%20of%20canceled,no%20room%20for%20nasty%20surprises.>
- <https://www.sciencedirect.com/science/article/pii/S2352340918315191>
- <https://towardsdatascience.com/decision-trees-understanding-the-basis-of-ensemble-methods-e075d5bfa704>
