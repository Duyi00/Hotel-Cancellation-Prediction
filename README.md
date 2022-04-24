# Hotel Cancellation Prediction

In this data science project, we will be utilising data from `hotel_bookings.csv` to answer the following question:

**Problem: Predict whether a Hotel Reservation will be Cancelled based on Variables _[To Be Determined]_**.

For a detailed walkthrough, please view our source code in order from: 

1. [Data Preparation](https://nbviewer.org/github/Duyi00/Hotel-Cancellation-Prediction/blob/main/data-preparation.ipynb)
2. [Exploratory Analysis (Variables 1 to 12)](https://nbviewer.org/github/Duyi00/Hotel-Cancellation-Prediction/blob/main/exploratory-analysis-pt_1.ipynb)
3. [Exploratory Analysis (Variables 13 to 24)](https://nbviewer.org/github/Duyi00/Hotel-Cancellation-Prediction/blob/main/exploratory-analysis-pt_2.ipynb)
4. Machine Learning and Conclusion

Please note that the above hyper-links will open a notebook viewer, in order to render the interactive Plotly figures.

## 1015.ipynb
Our notebook is split into **3** sections:

<div style="background-color: #ebf4f7; color: #595959; text-align:left; vertical-align: middle; padding: 15px 25px 15px 25px; line-height: 1.6;">
<div style="font-size:20px"><b>1) Data Cleaning and Preparation</b></div>
<p>Using <code>NumPy</code> and <code>Pandas</code>, we massaged the raw data into usable forms. Without going into details, we:</p>
<ul>
    <li>Handled Missing Data.</li>
    <li>Removed Extreme Outliers.</li>
    <li>Handled with `datetime` series to change it into desirable forms.</li>
</ul>
  <p> </p>
<div style="font-size:20px"><b>2) Exploratory Data Analysis (EDA)</b></div>
  <p>Performed EDA on <b>24</b> different variables. We utilised:</p>
<ul>
    <li><code>Plotly</code>, <code>Seaborn</code>, <code>Matplotlib</code>.</li>
</ul>
  
<div style="font-size:20px"><b>3) Machine Learning</b></div>
  <p>Using <code>sciKit-learn</code>, we implemented models such as:</p>
<ul>
    <li>Decision Tree Classifier.</li>
    <li>Random Forest Classifier.</li>
    <li>Gradient Boost Classifier.</li>
    <li>Ada Boost Classifier.</li>
    <li>Cat Boost Classifier.</li>
    <li>XGBoost Classifier.</li>
    <li>Logistic regression.</li>
</ul>
    </div>


## Conclusion and Recommendations

In conclusion, we decided to utilise the **Random Forest Classifier** as our final model. This is due to its high accuracy of ~**85%** and relatively low False Positive Rate of ~**8%**.


We have also came up with the following recommendations based on our findings to allow hotels maximise utilisation of their rooms.

- Lead time : Allow reservations up to 200 days in advance, chance of cancellation increases linearly from there to 400 days. 
- Day/Month : Thursday - Saturday especially during April - October have higher cancellation rates. Allow for more over-booking during this period.


## Authors

- [@Duyi00](https://github.com/Duyi00): Data Preparation and Cleaning, Data Visualization.
- [@zihan15](https://github.com/zihan15): Machine Learning.
- [@pebblepaw](https://github.com/pebblepaw): Data Preparation and Cleaning, Data Visualization.

## References
- <https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand>
- <https://www.datacamp.com/community/tutorials/understanding-logistic-regression-python>
- <https://blog.experience-hotel.com/where-do-cancellations-come-from/#:~:text=Average%20cancellation%20rates&text=The%20average%20percentage%20of%20canceled,no%20room%20for%20nasty%20surprises.>
- <https://www.sciencedirect.com/science/article/pii/S2352340918315191>
- <https://towardsdatascience.com/decision-trees-understanding-the-basis-of-ensemble-methods-e075d5bfa704>
