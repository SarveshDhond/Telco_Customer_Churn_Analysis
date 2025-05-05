# CUSTOMER CHURN ANALYSIS - PYTHON
In this project, I analyzed customer churn rates concerning other variables.

## DATA SOURCE
[www.kaggle.com](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
## PROJECT AIM
This project aims to showcase my Python and analysis skills. 

PROJECT PREREQUISITE
1. Python
2. Jupyter notebook
3. Deepseek

## STEPS TAKEN
- Importing libraries and files required
- Data Wrangling/cleaning
- Data Analysis

## ANALYSIS BASED ON VARIABLES
### 1. Total number and percentage of customers churned out
This chart shows a total of 5,174 customers who did not churn and 1,869 customers who did churn. This indicates a churn rate of approximately 26.5% ( as shown in the pie chart).
Understanding this overall rate is crucial for assessing the health of customer retention efforts.
The majority of customers are retained, which suggests that current retention strategies are somewhat effective. However, the significant number of churned customers (1,869) highlights areas for improvement.

![Customer churned](https://github.com/user-attachments/assets/b1f53ad0-1e01-463d-ae8d-03b877455219)
![Customer Churned in percentage](https://github.com/user-attachments/assets/dec75983-9877-422a-8996-7f27cc8ed7c2)

### 2. Churn rate based on gender
This chart shows the distribution of churn across different genders (Female and Male). It would be useful to analyze whether there is a significant difference in churn rates between genders. The chart shows the same level of churn in both genders. 

![Customer churn based on gender](https://github.com/user-attachments/assets/798b8a87-efdd-4cb5-a119-2b3efed99b58)

### 3. Churn rate based on age
This count plot shows how different age groups, particularly senior citizens, impact customer churn. It would be useful to analyze whether older customers (senior citizens) are more or less likely to churn compared to younger age groups.
The chart indicates a higher churn rate among senior citizens, which suggests that this demographic is less satisfied with the service or finds it less suitable for their needs.
Understanding the churn behaviour of different age groups can help develop targeted retention strategies. For instance, if senior citizens have a higher churn rate, tailored offers or services might be necessary to retain them.

![Customer churn based on age](https://github.com/user-attachments/assets/37776437-5347-4319-b7d7-04ad7d26172b)
 
### 4. Churn rate based on contract tenure
This plot illustrates the relationship between the length of contract tenure and customer churn. It would be useful to analyze whether customers with shorter tenures are more likely to churn compared to those with longer tenures.
The chart shows higher churn rates in the early months, which indicates that new customers are more likely to leave. This could be due to initial dissatisfaction or the lack of established loyalty.
The data suggests the need for stronger retention strategies for new customers, such as onboarding programs, early engagement initiatives, or special offers to build loyalty from the start.
Lower churn rates for customers with longer tenures indicate higher satisfaction and loyalty among long-term customers. Recognizing and rewarding these customers might further enhance their loyalty.

![Customer churn based on contract tenure](https://github.com/user-attachments/assets/10b62936-7a46-42f0-a181-c37aaf84fb65)
![Further customer churn vs tenure](https://github.com/user-attachments/assets/fc6dcd39-8cbf-4301-a997-07d7fbc8465c)

### 5. churn rate based on additional services offered 
The series of charts compare churn rates between customers who use various additional services (e.g., PhoneService, MultipleLines, OnlineBackup, OnlineSecurity, StreamingTV, StreamingMovies, TechSupport, DeviceProtection) and those who do not. It would be useful to analyze how the usage of these services impacts churn.
Customers using multiple lines  have higher churn rates compared to those using a single line.
Analyzing churn rates for specific services like OnlineSecurity, Online Backup, Tech support, Streaming TV and Streaming movies reveals which services are most effective in retaining customers. Lower churn rates among customers not using these services indicate the value of cross-selling these services.

![Customer churn based on other services](https://github.com/user-attachments/assets/7a4eb1ae-4719-4502-a9ff-e28a6e3fc3b2)

### 6. Churn rate based on method of payment
This chart shows the distribution of churn across different payment methods (Electronic check, Mailed check, Bank transfer and Credit card). It would be useful to analyze whether certain payment methods are associated with higher churn rates.
the chart indicates a higher churn rate among customers using electronic checks, it might suggest issues with this payment method, such as inconvenience or lack of trust. This could prompt a review of the electronic check process to improve customer experience. Other methods of payment have similar levels of churn. 

![Customer churn based on their method of payment](https://github.com/user-attachments/assets/3ad12ecf-ff84-43d0-baaa-9d1ad1ae6cdc)

## CONCLUSION
In conclusion, approximately 26.5% of customers churn, indicating a significant area for improvement in retention strategies.
Senior citizens have higher churn rates compared to younger customers, suggesting the need for age-specific retention strategies.
Customers with shorter tenures are more likely to churn, highlighting the importance of early engagement and onboarding programs.
Usage of additional services is associated with lower churn rates, emphasizing the value of these services in customer retention.
Customers using automatic payment methods (Bank transfer and Credit card) tend to have lower churn rates, suggesting that convenience and automation contribute to retention.
