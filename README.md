# 🏥 **Health Insurance Cost Prediction — ML Project Overview**
🎯 **Business Problem**

The majority of the countries finalize health insurance costs based on many factors such as age, number of people in families, etc. What should be the actual health insurance price for an individual or a family is an issue for many companies. Hence, one insurance company hired you as a data scientist to predict the health insurance cost for possible future customers. They have already collected samples required to perform all data analysis and machine learning tasks. your task is to perform all data analysis steps and finally create a machine learning model which can predict the health insurance cost.

📊 **Dataset Features**

1.age – primary person’s age
2.sex – gender (female/male)
3.bmi – body mass index (kg/m²)
4.children – number of dependents
5.smoker – yes or no
6.region – the beneficiary’s residential area in the US, northeast, southeast, southwest, northwest.
7.charges – actual insurance cost (target)

**🔍 Exploratory Data Analysis (EDA) Tasks**

1.Checking the data types, shape, and summary statistics of the data
2.Handling missing values and outliers
3.Plotting histograms, boxplots, and density plots to examine the distribution of each variable
4.Plotting scatterplots, correlation matrices, and heatmaps to explore the relationship between variables
5.Engineer and transform features to enhance model performance

Some of the essential patterns that are found in the given data using the EDA approach are:

The insurance cost is positively correlated with age, bmi, and smoking habit, and negatively correlated with the number of children The insurance cost is higher for smokers than non-smokers, and for females than males The insurance cost varies across different regions, with the highest in the southeast and the lowest in the southwest

Gradient boosting Regressor is one of the most effective techniques for building machine learning models for health insurance cost prediction.Here Gradient boosting Regressor model outperformed other regression models such as Simple Linear Regression,Support Vector Regression, Random forest Regressor in predicting health insurance costs. The Gradient Boosting Regressor consistently delivered the best accuracy


**Summary**

• Insurer-relevant factors: age, BMI, smoking status, children, region
• Strong cost drivers: age & smoking
• Gradient Boosting Regressor emerged as the best-fit model—ideal for predicting insurance charges

