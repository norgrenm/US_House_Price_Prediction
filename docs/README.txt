Group 3: Elio Aybar, Cristal Garcia, Sunny Li, Matt Norgren, Jingyi Tang
Data Mining Project Proposal: Housing Price Predictions

Business Problems (Considering 2 Proposals to Explore):
* Build a model that uses historical data to predict future housing prices. Features may include historical home sales price, macroeconomic data, public school density, grocery density, hospital ratings, stores location (Starbucks, Target)
* Do features affecting the housing price change over time? We can divide the time series data into two parts (for example, 1996-2006, 2007-2017), and build a model for each time period to detect whether the determinant features affecting house prices have changed.  (Compute the frequency of each feature which occurs as an optimal feature in all models.)
Data sources:
Kaggle -  Zillow Economics Data (https://www.kaggle.com/zillow/zecon )
       Housing data from April 1996 through August 2017 related to US domestic home sales. The dataset offers insight into housing types, delineation between bedroom/bathroom count, square footage, by state, count, and neighborhood in some instances. 
Feature / Model Engineering: 
1. Data cleaning (missing data, merge data)
2. Feature Engineering 
3. Model training (test as much algorithm as possible, possible models include Random Forest, Gradient Boosting, Ada-Boosting, Voting Classifier...)
4. Hyperparameter tuning (Back Test, Grid Search)
5. Model accuracy test (Mean absolute error, RMSE, Confusion Metrics, train-test split)
Business Value / Contribution:
If exploration of the features changing over time is the focus, the better understanding of trends will help potential sellers understand where to focus on resale and potential buyers better articulate what they are looking for. 
Tentative Roles of Each Member: team will be working collaboratively on master file via GitHub on all roles but leads will be assigned to each section.  
Elio: Data Cleaning / Multiple linear regression
Cristal: Data Cleaning / Feature Engineering / Random Forest/ SVM
Sunny:  Model training / Hyperparameter tuning / PCA
Matt: Data Cleaning /  Ada Boosting
Jingyi: Model training / Gradient Boosting 
Appendix: Potential data to consider once zero in on region based on primary Zillow Economic Data set
Kaggle - Food Deserts in the US (https://www.kaggle.com/tcrammond/food-access-and-food-deserts)
Kaggle - Hospital Ratings (https://www.kaggle.com/center-for-medicare-and-medicaid/hospital-ratings)
Kaggle - USA Public Schools (https://www.kaggle.com/carlosaguayo/usa-public-schools)
       Public Schools (k-12) in US for 2014-2015 as defined by Common Core Data, National Center for Education Statistics,  and US Department of Education. 
Kaggle - Starbucks locations (https://www.kaggle.com/starbucks/store-locations)
Kaggle - Target locations (https://www.kaggle.com/ben1989/target-store-dataset)
Economic Data - fed funds rate, inflation, median income (https://fred.stlouisfed.org)



1



Aybar, Garcia, Li, Norgren, Tang





