# IIM-Captstone-Bank-Loan-Prediction-using-ML
Predicting whether or not people tend to opt for a loan over discounted rates
Business Problem:
A group of customers were given an offer in person that they can get a loan at discounted rate and
processing fee will be waived off. A pilot campaign was conducted to get response from customers
whether they are interested in taking out a loan or not. Response was recorded and data was collected.
Based on data given we need to:
1) Build a model to predict whether customers will be interested in taking out a loan or not.
2) Identifying features which are most important
3) In case of black box models e.g. Random forest use SHAP, LIME to figure out features affecting
the target variable
4) Approaching a customer has costs involved with it, hence find the profitable segments so that
more customized marketing can be done.
5) Model will be needed on a monthly basis as this data gets updated each month.
Variables involved
● Customer_id
● Age
● Gender
● Balance
● Occupation
● No of Credit transaction
● SCR
● Holding period

Task List
[x] Build a model to predict whether customers will be interested in taking out a loan or not.
[x] Identifying features which are most important
[x] In case of black box models e.g. Random forest use SHAP, LIME to figure out features affecting the target variable
[x] Try Unsupervised clustering models
[x] Remove Unnecessary Models from the File
[x] Generate synthetic data for model.
[x] Approaching a customer has costs involved with it, hence find the profitable segments so that more customized marketing can be done.
[x] Need to write inferences what is going on
[x] Matrix evaluation for all 20% above models
[x] KS Scaling
[x] Variance Inflation Factor (VIF)
[x] Bucketing Age and SCR
[x] Business Output
Variables involved: Customer_id, Age, Gender, Balance, Occupation, No of Credit transaction, SCR, Holding period

Understanding Complex Variables
Holding Period (How long the customer is able to hold the money in his account.. So, if they have some existing expenses like a loan EMI or any other monthly expense which gets deducted, usually the first week of every month, hence it makes the balance in the account lower during initial days of the month itself.Higher the holding period, more stable their money is in the account.)

SCR SCR is a score given to a customer for a particular product ( in this case loan ) based on certain parameters, to know whether how likely that customer is to buy that product.. so, higher the score, higher the probability, the customer will buy it. SCR propensity of a customer to respond to a digital marketing

Business Conclusion
HOLDING PERIOD Vs AVG BALANCE
The avg holding period and avg balance tend to show high collinearity as they are directly proportional and it can be verified from "Misc_Dash".

Self employed class in both genders were able to hold money in their account for a long time resulting in high balance amount.

Which Category of Customers Tend to opt for Loans?
Customers with the below traits tend to be inclined towards opting for a loan;

Females who own small business/self-owned (SENP) business show higher SCR.

Males who are self employed (SELF-EMP) show higher SCR .

High SCR's but least holding period i.e. who tend to have EMI's or other deductions from their account.

Higher Avg credit transactions shows that the customer is more likely to opt for a loan. As Credit transactions show direct proportionality to SCR values.

Final Conclusions
From the given data it can be observed that in Females Self Employed tend to be the early bread earners whereas in case of Males Small Business owners tend to be the early bread earners.

For both the genders higher avg balance amount is observed in the accounts of Small business owners, second highest avg balance is observed for Professionals (PROF) category customers.

Which Category of Customers TEND NOT TO OPT for Loans?
In Males, Salaried & Professional class employees tend to not opt for loans as they must have constant inflow of cash.

In Females, Professional class employees tend to not opt for loans.

In both the genders, customers showing higher holding period tend to not opt for loans as there are less deductions over long time periods.
