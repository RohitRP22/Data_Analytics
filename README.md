#Dataset Description
First give a brief introduction to all attributes in the dataset we use:

# People

•ID: Customer's unique identifier
•Year_Birth: Customer's birth year
•Education: Customer's education level
•Marital_Status: Customer's marital status
•Income: Customer's yearly household income
•Kidhome: Number of children in customer's household
•Teenhome: Number of teenagers in customer's household
•Dt_Customer: Date of customer's enrollment with the company
•Recency: Number of days since customer's last purchase
•Complain: 1 if customer complained in the last 2 years, 0 otherwise

# Products

• MntWines: Amount spent on wine in last 2 years
• MntFruits: Amount spent on fruits in last 2 years
• MntMeatProducts: Amount spent on meat in last 2 years
• MntFishProducts: Amount spent on fish in last 2 years
• MntSweetProducts: Amount spent on sweets in last 2 years
• MntGoldProds: Amount spent on gold in last 2 years

# Promotion

• NumDealsPurchases: Number of purchases made with a discount
• AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise
• AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
• AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
• AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise
• AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise
• Response: 1 if customer accepted the offer in the last campaign, 0 otherwise

# Place

• NumWebPurchases: Number of purchases made through the company’s web site
• NumCatalogPurchases: Number of purchases made using a catalogue
• NumStorePurchases: Number of purchases made directly in stores
• NumWebVisitsMonth: Number of visits to company’s web site in the last month

# Marketing Campaign Result Prediction using Logistic Regression
•	Data contains 2240 instances with 29 features
•	Steps include Feature Engineering, Exploratory Data Analysis, Outlier Treatment
•	Class imbalanced of 85:15 was handled using SMOTE
•	Result: - Accuracy = 90.1, Precision = 91.6, Recall = 88.35, ROC Score = 0.905 with Threshold = 0.4391

