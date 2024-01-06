# Big-Data--Analysis-and-prediction-of-Advertising-and-Marketing-Data
The data was obtained from Kaggle "Uplift Modeling, Marketing and Campaing Data" provided by AI lab of Criteo (French advertising company that provides online display adverstisements). The data contains 13 million instances from a randomized control trial collected in two weeks, where 84.6% of the users where sent the treatment [1].
Each instance has 12 features that were anonymized plus a treatment variable and two target variables (visits and conversion). There is another extra variable called "exposure" which indicates whether the user was effectively exposed to the treatment.
As mentioned before, there are two target variables (visits and conversion), this notebook will only focus on the conversion variable. Which can be understood as the indicator whether the user bought the product.
The goal is to generate a model that can identify users that are more likely to convert (or buy the product) and avoid the ones that are not.
Before the modeling approaches, it is necessary to select the data that is useful for the models.
The models are Logistic Regression and RandomForest,GBT and uplifting.
