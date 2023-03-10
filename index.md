---
layout: default
---

Welcome to my portfolio page! Here are the projects I did or am doing.

# Playstudios Loyalty Program Engagement Model (In Progress)

- xxxx
- 

# SpaceY Successful Landing Prediction

- Collected data from public SpaceX API and SpaceX Wikipedia page. Cleaned data and gathered relevant columns to be used as features to predict successful landings.

- Explored data using SQL, visualization, folium maps, and [dashboard](https://space-y-dashboard.onrender.com/). Explored and visualized the correlation between successful landings and other features.

- Four machine learning models were produced: Logistic Regression, Support Vector Machine, Decision Tree Classifier, and K Nearest Neighbors to predict successful landings.

- Used GridSearchCV to find the best parameters for machine learning models. All models had similar results, with an accuracy rate of about 83.33%.

![pic1](https://github.com/Doravado/samuel_portfolio/blob/main/image/My%20project-1.png)

![pic2](https://github.com/Doravado/samuel_portfolio/blob/main/image/space_y.png)

>[Learn More Details](https://github.com/Doravado/space_y/blob/main/image/ds-capstone-chongxinzhao.pdf)

<br/>

# USA Airline Delay Cause Analysis

- Cleaned the data of USA airline delay cause (data source: [Federal Aviation Administration](https://www.faa.gov/data_research)). Handled missing values, merged date time, and delimited geographic information.

- Analyzed and visualized the data from multiple perspectives and generated insights on time series features, delay cause, and geographic information.

- Used Holt-Winters model and forecasted Austin Airport performance in 2023. Created and deployed the performance [dashboard](https://austin-ariport-delay-cause-dashboard.onrender.com) (click to see).

- In Oct 2022, I presented insights on choosing the least-likely-delayed airlines during the 2022 Thanksgiving holiday to classmates at UT Austin. I got some positive feedback about the accuracy of my models and insights after the holiday.

![alt text](https://github.com/Doravado/samuel_portfolio/blob/main/image/dashboard2.png)

>[Learn More Details](https://github.com/Doravado/usa_airline_delay_cause)

<br/>

# iFood Customer Data EDA

- Created a new column as the unique identifier. Made a boxplot for each column and removed the outlier data. Visualized each column’s data distribution with histograms.

- Used cluster map, catplot, regplot to visualize the correlation between variables. Picked the optimal X variables to predict customer response, based on random forest results.

- Fitted the train data into three models (logit, probit, and c-log-log). Probit regression may be the best model for the data, with 87% accuracy after optimization.

- Plotted a histogram of response probability. The business can use the model to target customers who are more likely to respond and save more marketing costs.

![alt text](https://github.com/Doravado/samuel_portfolio/blob/main/image/confusion_matrix.png)
![alt text](https://github.com/Doravado/samuel_portfolio/blob/main/image/hist.png)

>[Learn More Details](https://github.com/Doravado/ifood_customer_data)

<br/>
