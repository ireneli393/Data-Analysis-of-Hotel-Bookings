# Data-Analysis-of-Hotel-Bookings

Project Overview:

We conducted an in-depth analysis of a hotel booking dataset using various statistical methods and machine learning models. Our key findings include:

Booking Patterns: We observed a significant, though small, difference in the average daily rate between canceled and non-canceled bookings for both resort and city hotels. This was analyzed using Power Analysis, Mann-Whitney U Test, and Effect Size.

Cancellation Insights: Canceled bookings tend to have a longer lead time compared to non-canceled ones. Before applying the Random Forest classifier for predicting cancellations, we used KMeans clustering to mark and segment the data. The Random Forest model was particularly effective for a cluster of young adults without kids, who are more flexible in their plans.

Predictive Modeling: We developed a multiple linear regression model to predict the length of stay, identifying the number of people as a significant predictor.

Assumptions:
1. Normality of data for the t-test.
2. Continuous, independent data with similar distributions for the Mann-Whitney U test.
3. Linear relationships and normal, independent residuals for multiple linear regression.
   
Limitations:
1. The dataset spans 2015-2017, limiting its relevance for post-pandemic analysis.
2. Data is from only two hotels, which may not generalize to others.
3. Some variables are skewed, and ideally, post-pandemic data from a larger variety of hotels, like those from a platform such as Expedia, would be more ideal.

Data Source: https://www.kaggle.com/datasets/mojtaba142/hotel-booking
