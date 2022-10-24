# Mid-Bootcamp-Project
## Project Brief/Summary
Every company now and then needs to launch different marketing campaigns in order to improve their conversion rates. The goal of this project is to predict the customers who will accept campaigns. 
## Data Collection
Data has been collected from Kaggle.It consists of 2240 datapoints. Definition of different features is as fellow: 
- AcceptedCmp1 - 1 if customer accepted the offer in the 1st campaign, 0 otherwise
- AcceptedCmp2 - 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
- AcceptedCmp3 - 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
- AcceptedCmp4 - 1 if customer accepted the offer in the 4th campaign, 0 otherwise
- AcceptedCmp5 - 1 if customer accepted the offer in the 5th campaign, 0 otherwise
- Response (target) - 1 if customer accepted the offer in the last campaign, 0 otherwise
- Complain - 1 if customer complained in the last 2 years
- DtCustomer - date of customer’s enrolment with the company
- Education - customer’s level of education
- Marital - customer’s marital status
- Kidhome - number of small children in customer’s household
- Teenhome - number of teenagers in customer’s household
- Income - customer’s yearly household income
- MntFishProducts - amount spent on fish products in the last 2 years
- MntMeatProducts - amount spent on meat products in the last 2 years
- MntFruits - amount spent on fruits products in the last 2 years
- MntSweetProducts - amount spent on sweet products in the last 2 years
- MntWines - amount spent on wine products in the last 2 years
- MntGoldProds - amount spent on gold products in the last 2 years
- NumDealsPurchases - number of purchases made with discount
- NumCatalogPurchases - number of purchases made using catalogue
- NumStorePurchases - number of purchases made directly in stores
- NumWebPurchases - number of purchases made through company’s web site
- NumWebVisitsMonth - number of visits to company’s web site in the last month
- Recency - number of days since the last purchase
## Steps
### 1. Data Cleaning and Exploration
All the features of dataset has been explored and cleaned. New features has been added and redundant were removed. 
### 2. EDA at Tableau
>https://public.tableau.com/app/profile/sadaf.shahbaz/viz/Book1_16653208859190/Mostlyconsumedproduct?publish=yes>
### 3. Modeling with and without Outlier
Different models has been applied, logistic regression, random forest, decision tree, and KNN. Best performance was achieved with logistic regression using hyper parameters tuning and and without removing outliers.
### 4. Building Confidence Interval
Confidence Interval was built on best performed model(i.e. logistic regression with hyper parameters).
### 5. Clustering and Classification
Lastly Unsupervised and supervised machined has been combined in order to get best outcome and get best target clusters for the analysis. From the anaylsis two clusters provided us best results. The best way to formulate any kind of campaigns is to use clusterig as a preprocessing and then classify it. After classification each company can decide which is most suitable strategy for each cluster.
Next step can be to improve the models(use more advancecd modelels, e.g. random forest, decision tree) with clustering and classification.


