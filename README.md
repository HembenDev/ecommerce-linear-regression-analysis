
## 🧠 Linear Regression on E-Commerce Dataset

This project applies **Linear Regression** to an **e-commerce dataset** containing 500 customer records and 8 features sourced from **Kaggle**. The goal was to explore how various customer behavior metrics — such as time spent on the website, time on the app, and length of membership — influence their **yearly spending**.

### 🔍 Key Steps

* **Exploratory Data Analysis (EDA):** Visualized relationships using joint plots and pair plots to detect correlations between key variables.
* **Correlation Analysis:** Found that **Length of Membership** showed the strongest positive correlation (**r = 0.8091**) with **Yearly Amount Spent**.
* **Model Development:** Built a regression model using **Scikit-learn**, training on 70% of the data and testing on 30%.
* **Model Evaluation:**

  * Mean Absolute Error (MAE): 8.43
  * Mean Squared Error (MSE): 103.92
  * Root Mean Squared Error (RMSE): 10.19

A **scatter plot** of predicted vs. actual values indicated strong model performance and minimal error.

### 🧩 Tech Stack

* **Python**
* **Pandas, NumPy**
* **Matplotlib, Seaborn**
* **Scikit-learn**

### 📊 Insights

* Customer **membership duration** is the strongest predictor of annual spending.
* **Time on App** contributes more significantly than **Time on Website** to customer purchases.

---

### 🏷️ Tags

`#DataScience` `#MachineLearning` `#LinearRegression` `#EDA` `#Python` `#ScikitLearn` `#DataAnalytics` `#Kaggle` `#RegressionAnalysis`


