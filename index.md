---
layout: default
---

Welcome to my projecct portfolio page! 

Please feel free to share any suggestions you may have regarding my projects. Thank you!🥳

# 🤘My Skills
- **Professional Skills:** Leadership, Communication and Presentation, Teamwork, Multi-task Management

- **Marketing:** Marketing Management, Consumer Insights, Digital Marketing, Media Strategy

- **Analytics:**  A/B Testing, Predictive Analysis (Linear Regression, Logistic Regression, Time Series Forecasting), Clustering, Classification, Conjoint Analysis, Survival Analysis, CLV Analysis, Pricing Analysis, Campaign Analysis

- **Python (1+ years):** Pandas, Numpy, Matplotlib, Seaborn, Plotly, Statsmodels, Sklearn

- **SQL (1+ years):** Advanced Joins, Subqueries, Window Functions, MySQL, Snowflake

- **Others:** Excel (3+ years), Powerpoint (3+ years), R (1+ years), Tableau (1+ years)

![](/image/skills.png)

<br/>

# 🎮Playstudios Loyalty Program Engagement Model (In Progress)
- Led a team of four to drive project progress and was mainly responsible for communicating with clients and other parties to coordinate tasks and timelines.

- Collaborated with teammates to build project methodology. Used snowflake, SQL, and python to process 2 million player data independently, including querying and cleaning data and creating model variables.

- Used machine learning to do player segmentation and classification. Did survival analysis and built a retention model to identify early characteristics of loyal players.

- Based on insights from player analysis and models, our team is now designing a marketing campaign to activate potential loyalty players with highly efficient campaign methods.

- Made decks and communicated project methodology and outcomes to client, synthesizing technical analysis into simple and clear terms.

![](/image/playstudios_project2.png)

<br/>

# 🏅McCombs Marketing Case Challenge of SAMSUNG
- Won the 3rd place against MSM and MBA teams in case competition judged by Fortune 500 executives.

- Collaborated with teammates and recommended a blue ocean strategy for SAMSUNG to gain Gen Z customers in the U.S. by utilizing 3+ marketing models and qualitative research.

- Responsible for qualitative analysis of customer segmentation, media strategy, campaign effect, and budget recommendation.

- Presented the final strategy and marketing campaign plan to judges with teammates. Answered judges' questions and communicated strategy thought processes.

### Key Insights
- **Target Segment:** Based on our analysis, within Gen Z Girls, the Gen Z Girl Gamer has the highest potential and alignment with SAMSUNG's product portfolio.

- **Emerging Market:** Almost all Gen Z Girls already have a phone. So, to break into the market, targeting wireless audio is the most ideal because it is an emerging market.

- **Current Positioning:** We noticed a potential new market of wireless audio for gaming with no other major competitors for SAMSUNG Galaxy Buds.

- **Proposed Campaign:** We propose a campaign called #AllYou based on Gen Z’s psychographics. This campaign will build empathy with consumers through sponsored streams of influencers.

- **Break Into Niche & Conquer:** We can decrease customers’ switching costs by using earbuds as a stepping stone to build brand equity. Ultimately, we can get Gen Z switch to the whole SAMSUNG’s product portfolio.

![](/image/samsung.png)

> [Learn More Insights](https://docs.google.com/presentation/d/1g4WpDGZbBQX3FzKpIPkti4ToArg9n9XVMEuoRXJYfAQ/edit?usp=sharing)

<br/>

# 🛬USA Airline Delay Cause Analysis
- Cleaned the data of USA airline delay cause (data source: [Federal Aviation Administration](https://www.faa.gov/data_research)). Handled missing values, merged date time, and delimited geographic information in python.

- Analyzed and visualized the data from multiple perspectives and generated insights on time series features, delay cause, and geographic information.

- Used Holt-Winters model and forecasted Austin Airport performance in 2023. Optimized the models and increased the accuracy by 5% on average. Created and deployed the performance [dashboard](https://austin-ariport-delay-cause-dashboard.onrender.com) (click to see).

- In Oct 2022, I presented insights on choosing the least-likely-delayed airlines at Austin Airport during the 2022 Thanksgiving holiday in class. After holiday, my classmates gave me some positive feedback about the accuracy of the models according to their holiday travel experience.

### Key Insights
#### Time Series Analysis
  - In 2022, flight traffic will return to the pre-pandemic level while still much lower than in 2019. On average, the number of arriving flights is highest in August and lowest in February.

![](/image/airline/flightnumber.png)

  - From 2003 to 2022, the total delay minutes fluctuate severely since the variance magnitude of delay minutes is much bigger than that of arriving flights. On average, the delay minutes reach the highest point in July and lowest in September.

![](/image/airline/delayminutes.png)

  - There is an asymmetry between the seasonality of the number of arriving flights and delay minutes. 

#### Delay Cause Analysis
  - 'Late_aircraft_delay' generate the most delay minutes every month.

  - Delay minutes hit the peak during Jun and Jul, though flight traffic does not reach the highest point until August. 
  
  - In June, both 'carrier_delay' and 'weather_delay' percentage increase. According to meteorological records, June and July, in particular, are the peak months for severe thunderstorms with high winds.

  -  In August, the percentages of 'carrier_delay' and 'nas_delay' jump up, which may be attributed to high flights this month.

![](/image/airline/delaycause.png)

#### Geographic Information Analysis
  - California and Texas rank at the top regarding the number of arriving flights and delay minutes due to their large population. Florida is climbing to a higher rank as more people want to go to warm-weather destinations.

![](/image/airline/animated_map.gif)

#### Austin Airport Performance Forecast
  - Total delay minutes of Austin airport increases over time. There is an evident seasonality of delay minutes. It reaches a peak in August and then goes down in the rest of the months in the year. However, it goes up a little bit in Oct and Dec.

  - Based on the Holt-Winters model forecast, Nov is the lowest point in the last three months of a year; it decreases by 18% compared with Oct 2022. So Nov may be an excellent time to travel by flight.

  - Nov is the lowest point for most airlines, same as the total delay minutes of Austin airport. Southwest may be the best-performing airline during Nov 2022.

![](/image/airline/dashboard2.png)

>[Learn More Insights](https://github.com/Doravado/usa_airline_delay_cause)

<br/>

# 🚀SpaceY Successful Landing Prediction
- Collected data from public SpaceX API and SpaceX Wikipedia page. Cleaned data and gathered relevant columns to be used as features to predict successful landings.

- Explored data using SQL, visualization, folium maps, and [dashboard](https://space-y-dashboard.onrender.com/). Explored and visualized the correlation between successful landings and other features.

- 4 machine learning models were produced: Logistic Regression, Support Vector Machine, Decision Tree Classifier, and K Nearest Neighbors to predict successful landings.

- Used GridSearchCV to find the best parameters for machine learning models. All models had similar results, with an accuracy rate of about 83.33%.

### Key Insights
#### Data Correlation
- 20 flights is a significant breakthrough that increased the landing success rate.

![](/image/spacey/flight_number.png)

- Landing appears to perform better in lower orbits or Sun-synchronous orbits.

![](/image/spacey/orbit.png)

- Landing success generally increases over time since 2013, with a slight dip in 2018. Success in recent years at around 80%.

![](image/spacey/launchtime.png){:width="50%"}

#### Landing Success Prediction
- All models had virtually the same accuracy on the test set at 83.33% accuracy. We likely need more data to determine the best model.

- SpaceY can use this model to predict whether a launch will have a successful landing to determine whether the launch should be made or not.

![](image/spacey/accuracy.png){:width="50%"}

>[Learn More Insights](https://github.com/Doravado/space_y/blob/main/image/ds-capstone-chongxinzhao.pdf)

<br/>

# 👤iFood Customer Data EDA
- Created a new column as the unique identifier. Made a boxplot for each column and removed the outlier data. Visualized each column’s data distribution with histograms.

- Used cluster map, catplot, regplot to visualize the correlation between variables. Picked the optimal X variables to predict customer response, based on random forest results.

- Fitted the train data into three models (logit, probit, and c-log-log). Probit regression may be the best model for the data, with 87% accuracy after optimization.

- Plotted a histogram of response probability. The business can use the model to target customers who are more likely to respond and save more marketing costs.

### Key Insights
#### Data Correlation
- 'Z_CostContact' and 'Z_Revenue' have no correlation with any variables, so I dropped the two features at first.

- The purchases of all kinds of products are highly correlated. Additionally, income and the number of kids are significantly correlated with many other variables.

![alt text](/image/ifood/clustermap.png){:width="80%"}

- Based on catplot and regplot, age and purchase amount are positively correlated. Each age has a broad range of purchase amounts tough.

![alt text](/image/ifood/catplot.png)

#### Modeling Customer Response
- Probit regression may be the best model to model customer response here. The accuracy score of the final model is around 87%.

![alt text](/image/ifood/confusion_matrix.png)

- According to regression coefficients, the longer the days since the consumer became the customer, the customer is more likely to respond to the promotion campaign.

![alt text](/image/ifood/probit2.png){:width="80%"}

- For the next campaign, the business can predict customer response probability based on their features and target customers more likely to respond. Targeting those customers rather than all customers can save more costs for the business.

![alt text](/image/ifood/hist.png)

>[Learn More Insights](https://github.com/Doravado/ifood_customer_data)

<br/>

# 🏢2022-2023 Layoffs Data Visualization
- Cleaned the data (data source: [Layoffs.fyi](https://layoffs.fyi/)) with Excel. 

- Visualized the data from multiple perspectives (including by country, by industry, by company) to show the distribution and timeline of the mass layoffs.

- Deployed the [dashboard](https://public.tableau.com/app/profile/samuel.zhao2703/viz/2022-2023Layoffs/Story1) (click to see) on Tableau Public.

### Key Insights
- Mass layoffs are sweeping worldwide, and the U.S. accounts for 69% of layoffs. Meanwhile, India and many European countries are also worst-hit areas.

- The consumer industry is experiencing the most severe layoff earthquake, while the manufacturing industry is least vulnerable.

- 21% of layoffs in the U.S. are from the consumer industry. While in other countries, employers from healthcare and other industries have the most layoffs.

- The layoff storm seemingly has no sign of stopping, and it is even accelerating in big countries, including America, China, and India.

![alt text](/image/tableau.png)

>[Learn More Insights](https://public.tableau.com/app/profile/samuel.zhao2703/viz/2022-2023Layoffs/Story1)

<br/>

# 💡More Projects Coming Soon...
**🎵Classical Music Market Data Analysis**

- Try to figure out why Apple designs a standalone music app for classical music. Why is it an emerging and profitable market?

**🏠Austin Rent Price Analysis and Forecast**

- Forecast Austin's rising rent based on Zillow public rent data and US census data (including demographics, employment, transportation, etc.)

<br/>

# 📱Contact Me

Please feel free to share any suggestions you may have regarding my projects. Thank you!🥳

- Phone: (737)-296-0548

- Email: samuel.zhao@utexas.com

- [🔼 Back To Top And Know More About Me](https://doravado.github.io/samuel_portfolio/)
