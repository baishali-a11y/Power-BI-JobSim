# Power-BI-JobSim
Second task of the PWC PowerBI Job Simulation

About the Dataset:
The dataframe has 7043 entries (rows) and 23 columns. The columns are:

1. `customerID`: Unique identifier for each customer. It is of object type.
2. `gender`: Gender of the customer. It is of object type.
3. `SeniorCitizen`: Indicates whether the customer is a senior citizen or not. It is of integer type.
4. `Partner`: Indicates whether the customer has a partner or not. It is of object type.
5. `Dependents`: Indicates whether the customer has dependents or not. It is of object type.
6. `tenure`: The number of months the customer has stayed with the company. It is of integer type.
7. `PhoneService`: Indicates whether the customer has a phone service or not. It is of object type.
8. `MultipleLines`: Indicates whether the customer has multiple lines or not. It is of object type.
9. `InternetService`: Type of internet service the customer has. It is of object type.
10. `OnlineSecurity`: Indicates whether the customer has online security or not. It is of object type.
11. `OnlineBackup`: Indicates whether the customer has online backup or not. It is of object type.
12. `DeviceProtection`: Indicates whether the customer has device protection or not. It is of object type.
13. `TechSupport`: Indicates whether the customer has tech support or not. It is of object type.
14. `StreamingTV`: Indicates whether the customer has streaming TV or not. It is of object type.
15. `StreamingMovies`: Indicates whether the customer has streaming movies or not. It is of object type.
16. `Contract`: The contract term of the customer. It is of object type.
17. `PaperlessBilling`: Indicates whether the customer has paperless billing or not. It is of object type.
18. `PaymentMethod`: The customer's payment method. It is of object type.
19. `MonthlyCharges`: The amount charged to the customer monthly. It is of float type.
20. `TotalCharges`: The total amount charged to the customer. It is of object type.
21. `numAdminTickets`: The number of administrative tickets raised by the customer. It is of integer type.
22. `numTechTickets`: The number of technical tickets raised by the customer. It is of integer type.
23. `Churn`: Whether the customer churned or not (Yes or No). It is of object type.

Analysis Done:
Using the churn dataset, Defined the proper KPIs and Created a dashboard for the retention manager reflecting the KPIs

To create a dashboard for the retention manager, we first need to define the Key Performance Indicators (KPIs). Here are some potential KPIs based on the churn dataset:

1. Churn Rate: This is the percentage of customers that stopped using your company's product or service during a certain time frame. You can calculate this by dividing the number of customers who churned during that time period by the total number of customers at the start of that period.

2. Retention Rate: This is the inverse of the churn rate. It's the percentage of customers you managed to retain over a certain period of time.

3. Average Revenue Per User (ARPU): This is the total revenue divided by the number of subscribers. This can be calculated monthly or annually.

4. Lifetime Value (LTV): This is the average revenue per user divided by the churn rate. It represents the total amount of revenue a business can reasonably expect from a single customer account.

5. Customer Acquisition Cost (CAC): This is the cost associated with convincing a potential customer to buy a product/service. This cost is incurred by the organization while convincing a potential buyer. This isn't directly available in the dataset but if the data is available, it can be a good KPI.

6. Net Promoter Score (NPS): This is a measure of how likely your customers are to recommend your products or services to their friends or colleagues. This isn't directly available in the dataset but if the data is available, it can be a good KPI.

7. Number of Support Tickets: This is the total number of support tickets raised by customers. This can be a measure of customer satisfaction and product quality.
