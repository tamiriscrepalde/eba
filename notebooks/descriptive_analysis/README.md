
<h2> Ifood Challenge </h2>

- **_AcceptedCmp1_**: 1 if customer accepted the offer in the first campaign, 0 otherwise
- **_AcceptedCmp2_**: 1 if customer accepted the offer in the second campaign, 0 otherwise
- **_AcceptedCmp3_**: 1 if customer accepted the offer in the third campaign, 0 otherwise
- **_AcceptedCmp4_**: 1 if customer accepted the offer in the fourth campaign, 0 otherwise
- **_AcceptedCmp5_**: 1 if customer accepted the offer in the fifth campaign, 0 otherwise
- **_Response_**: 1 if customer accepted the offer in the last campaign, 0 otherwise
- **_Complain_**: 1 if customer complained in the last two years
- **_DtCustomer_**: date of customer's enrollment with the company
- **_Education_**: customer's level of education
- **_Marital_**: customer's marital status
- **_Kidhome_**: number of small children in customer's household
- **_Teenhome_**: number of teenagers in customer's household
- **_Income_**: customer's yearly household income
- **_MntFishProducts_**: amount spent on fish products in the last two years
- **_MntMeatProducts_**: amount spent on meat products in the last two years
- **_MntFruits_**: amount spent on fruits in the last two years
- **_MntSweetProducts_**: amount spent on sweet products in the last two years
- **_MntWines_**: amount spent on wines in the last two years
- **_MntGoldProds_**: amount spent on gold products in the last two years
- **_NumDealsPurchases_**: number of purchases made with discount
- **_NumCatalogPurchases_**: number of purchases made using catalogue
- **_NumStorePurchases_**: number of purchases made directly in stores
- **_NumWebPurchases_**: number of purchases made through company's web site
- **_NumWebVisitsMonth_**: number of visits to company's web site in the last month
- **_Recency_**: numberof days since the last purchase


Questions to be answered:

1. How much data is there? Rows and columns
2. What are the numeric columns?
3. Is there duplicate data in the database? If yes, remove it.
4. Are there null values in the database? Do they indicate something? What to do with them?
5. What are the mean, median, percentiles 25 and 75, min and max of each numerical column?

Related to customer profile:

6. What is the biggest income in the database?
7. What is the distribution of incomes in the database? Are there customers that earn a lot and customers that earn little?
8. Does the customers have high or low levels of study?
9. How many customers are there in each marital status?

Related to how the data self correlate:

10. What is the relation between marital status and number of children? Does married people have more children?
11. Do people spend more or less on the platform when they have children?
12. Do people with higher income spend more?

Additional:

- What would you do with the information extracted from the above questions?
- Trace a business problem and ask as many questions as necessary to answer it.
