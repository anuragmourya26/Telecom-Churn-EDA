
Orange S.A., formerly France Télécom S.A., is a French multinational telecommunications corporation. The Orange Telecom's Churn Dataset, consists of cleaned customer activity data (features), along with a churn label specifying whether a customer canceled the subscription.

objective: Exploring and analyzing the data to discover key factors responsible for customer churn and coming up with ways/recommendations to ensure customer retention.

Understanding the business problem:

1) Customer churn in the telecom industry poses one of the most significant risks of loss of revenue.
2) The average churn rate in the telecom industry is approximately 1.9% per month. (US Data)
3) Since the cost of acquiring new customers is up to 25 times higher than the cost of retaining them, fostering customer loyalty is key.
4) With low switching costs and an abundance of alternative providers increased the rate of customer churn.

Detailed information about features of the dataset:

STATE: 51 Unique States name<br>
Account Length: Length of The Account<br>
Area Code: Code Number of Area having some States<br>
International Plan: Yes Indicate International Plan is Present and No Indicates no subscription for Internatinal Plan<br>
Voice Mail Plan: Yes Indicates Voice Mail Plan is Present and No Indicates no subscription for Voice Mail Plan<br>
Number vmail messages: Number of Voice Mail Messages ranging from 0 to 50<br>
Total day minutes: Total Number of Minutes Spent in Morning<br>
Total day calls: Total Number of Calls made in Morning.<br>
Total day charge: Total Charge to the Customers in Morning.<br>
Total eve minutes: Total Number of Minutes calls in Evening<br>
Total eve calls: Total Number of Calls made in Evening.<br>
Total eve charge: Total Charge to the Customers in Morning.<br>
Total night minutes: Total Number of Minutes calls in the Night.<br>
Total night calls: Total Number of Calls made in Night.<br>
Total night charge: Total Charge to the Customers in Night.<br>
Total intl minutes: Total Number of international calls in Minutes.<br>
Total intl calls: Total number of international calls made.<br>
Total intl charge: Total charges for international calls.<br>
Customer service calls Number of customer service calls made by customer<br>
Churn Customer: Churn, True means churned customer, False means retained customer<br>

Observation: 

There is correlation between churn and Total day minute/Total day charge, total eve calls and total eve charge and customer service calls.
Higher total day minutes or total day charge is responsible for customer chrun.
There is no significant relation between Total eve minutes with churn.
Some states have high churn percentage compared to other states.
42.41% of customers who have international calling plan have churned and 11.49 % of customers churned who don’t have international calling plan.
Data shows that if there are more 3 customer service calls the churn increases.

Final Recommendations:-
1. As per observation churn is high when the customer's Total Calling minutes per day is high. There may be some competitors who are offering cheaper calling rates so company should come up with optimal calling rate or launch a calling specific plan for customer retention.
2. In states (NJ, CA, TX, MD, SC ) where churn is high company needs to inspect if there is low network penetration or competitor are offering cheaper prices.
3. Customer with international calling plan churn 200% more than normal customers so this needs to be addressed with optimal international calling rate.
4. When there are more than 3 service calls the churn increases which mean there is need of resolving customers concerns for customer retention and satisfaction which lead to reduction in customer churn.


