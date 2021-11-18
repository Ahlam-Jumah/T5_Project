# T5_Project
Project Overview and Business Goals
Due to the evolving number of the banks and the strong competition between them,  banks look forward to increase their shar of the market by attracting more customers and maintaining the existing ones. According to [1], acquiring new customers is more costly than retaining the old ones. The studies show that improving the retention rate by up to 5 % can increase a bank’s profit up to 85 % [2]. This is define the significant need  of the bank to take into consideration their existing loyal profitable customers , maintain them, and trying to preventing them from leaving the bank. This could be achieved by the early prediction of the customers that might have a potentially to leave or discontinue using the bank services. s we know, it is much more expensive to sign in a new client than keeping an existing one. It is advantageous for banks to know what leads a client towards the decision to leave the bank. Churn. prevention allows banks to develop loyalty programs and retention campaigns to keep as many customers as possible [3].
For this purpose we aim in this project to develop a prediction model that is able to anticipate the customers that are willing to leave based on their pregiven records on the bank.
Success Metrics
From business point of view, the success metric will be applied to determine the success of our model to achieve its business goal.  The  basic churn rate formula is a good metrics, that clearly defined and it can be measured easily. churn rate is the percentage of customers that leave the bank over a given time period [4]. The Churn Rate Formula can be calculated as the number of churned divided by the total number of customers. By providing a point of comparison, we would be able to determining the model contribution of  minimizing the churn rate. 
Model
This project aims to develop a prediction model for customer churn in bank, by using a dataset of 10000 customers. Supervised learning model will be used for classification. 
Data
The utilized data for this project is publicly published. It is obtained from Kaggle website, and it can be accessed through the following link: Churn for Bank Customers | Kaggle. The dataset has 14 columns and 10,000 Rows, while the content of each dataset observation represents an individual customer with following features:
•	RowNumber—corresponds to the record (row) number and has no effect on the output.
•	CustomerId—contains random values and has no effect on customer leaving the bank.
•	Surname—the surname of a customer has no impact on their decision to leave the bank.
•	CreditScore—can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank.
•	Geography—a customer’s location can affect their decision to leave the bank.
•	Gender—it’s interesting to explore whether gender plays a role in a customer leaving the bank.
•	Age—this is certainly relevant, since older customers are less likely to leave their bank than younger ones.
•	Tenure—refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank.
•	Balance—also a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances.
•	NumOfProducts—refers to the number of products that a customer has purchased through the bank.
•	HasCrCard—denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank.
•	IsActiveMember—active customers are less likely to leave the bank.
•	EstimatedSalary—as with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries.
•	Exited—whether or not the customer left the bank.
Evaluation Metrices
The model performance will be evaluated against the following matrices:
•	Accuracy
•	Confusion matrix
•	Precision
•	Recall
•	F1 score
Tools
-	Jupiter Notebook & Python 3.
-	Python Libraries:
o	NumPy and Pandas for EDA.
o	Matplotlib and seaborn for visualization.
o	scikit-learn for modeling and evaluation.

References:
[1] Nie, G., Rowe, W., Zhang, L., Tian, Y., & Shi, Y. (2011). Credit card churn forecasting by logistic regression and decision tree. Expert Systems with Applications, 38(12), 15273-15285. 
[2] Verbeke, W., Martens, D., Mues, C., & Baesens, B. (2011). Building comprehensible customer churn prediction models with advanced rule induction techniques. Expert systems with applications, 38(3), 2354-2364
[3] Churn for Bank Customers | Kaggle.
[4] How to Calculate Churn Rate: 4 Churn Rate Formulas (profitwell.com)

