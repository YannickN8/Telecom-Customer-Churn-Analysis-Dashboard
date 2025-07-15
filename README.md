Telecom Customer Churn Analysis:


Summary:

Predicting customer churn is critical for telecommunication companies in order to effectively retain customers. It is more costly to acquire new customers than to retain existing ones. For this reason, large telecommunications corporations are seeking to develop models to predict which customers are more likely to change and take actions accordingly. So, what is customer churn? As per Wikipedia definition, customer churn, also known as customer attrition or customer turnover, is the loss of clients or customers. Customer churn rate is a key business metric in any industry and company providing services to end customers. In other words, “Keep your back door shut, don’t let your customer slip away.”

Companies usually make a distinction between voluntary churn and involuntary churn. Voluntary churn occurs due to a decision by the customer to switch to another company or service provider, involuntary churn occurs due to circumstances such as a customer's relocation to a long-term care facility, death, or the relocation to a distant location. In most applications, involuntary reasons for churn are excluded from the analytical models. Analysts tend to concentrate on voluntary churn, because it typically occurs due to factors of the company-customer relationship which companies control, such as how billing interactions are handled or how after-sales help is provided. This report will explain the various reasons for customer attritions, and recommendations on how to control these attritions. I used historical data on 7,043 customers including an indicator as to whether each customer churned.

<img width="1327" height="572" alt="01_Summary" src="https://github.com/user-attachments/assets/f3ef3d80-2285-4ebb-8b33-a57368077f6d" />



Raw Data Link: https://www.kaggle.com/datasets/shilongzhuang/telecom-customer-churn-by-maven-analytics

KPI’s:

1.    Total Number of customers Churned.
2.    Churn Rate %
3.    Churn Revenue %

Problem Statement: 

In this age of fierce competition, customer retention is one of the most important tasks for many companies. Telecommunications is known as one of the fast-growing industries in many countries. However, the average annual churn rate of the telecom industry is between 20–40%, which leads to huge loss of revenue. Customers always have a variety of choices, and they tend to choose the companies that can offer them better quality and less expensive services. To survive in this highly competitive market, telecom companies must develop strategies for attracting new customers or increasing the customer retention rate. It is noted that acquiring a new user costs 5 to 10 times more than retaining an existing one. Therefore, customer churn prediction has become a popular research area since it has the potential to help telecom companies to identify customers with high potential of terminating their contracts. Then, companies evaluate the situations and design appropriate service packages for these customers to retain them. It is extremely important for the company’s long-term development.

 <img width="730" height="387" alt="02_Problem Statement" src="https://github.com/user-attachments/assets/9729d81a-1b38-4b40-9d65-7639384004a7" />


 

Retaining a customer is the single most crucial thing that every organization should focus on for the following reasons:
 
 


1.    It costs up to 7x more to acquire a new customer than to retain an old one

2.    The probability of selling to an existing customer is 60-70%, while the probability of selling to a new prospect is only 5% to 20%

3.    65% of a company’s business comes from existing customers.

4.    Existing customers are 50% more likely to try new products.

5.    82% of companies agree that customer retention is cheaper than acquisition.


Key Performance Indicators (KPIs):

<img width="733" height="424" alt="03_Key Performance Indicators (KPI)" src="https://github.com/user-attachments/assets/e90fe553-679b-4afc-93f3-2042c69cb056" />


 


Data Dictionary:

<img width="1605" height="1111" alt="04_Data Dictionary" src="https://github.com/user-attachments/assets/ee813a32-02ed-4651-b748-ff2d244b749b" />


 

Executive Summary:

![05_Executive Summary](https://github.com/user-attachments/assets/2ae8ba41-eccb-4d09-8262-ed38abc47e36)


 


Problems encountered:     
1. Picking my first project was challenging. I want to pick something which I know and can talk about more. With plenty of customer service experience, the best project I can    work on is to find out Customer Churn. Now when I talk about customer churn, I mean all that trouble customers having to which make them take step of breaking relation and moving on. 
      
2. Finding the best data set was another challenge as there are not many dataset to look into, I was looking for the dataset with Year and exact location but unfortunately I find only the Zip code which I convert into State to put my graph together. 

3. Dataset was not clean it has multiple "blank" rows which was replaced. Dataset has Tenure by year column, so I have to convert tenure by month into Tenure by year by doing conditional formatting. I also created age bin for ages.

4. Using the perfect chart is important too. Its important to know your KPI's and what could be the best way to showcase the KPI's in different chart.

<img width="757" height="395" alt="06_Problem Incountered" src="https://github.com/user-attachments/assets/a8675890-75f1-4111-a03b-75a93b8df0ce" />

 


Key Insights & Takeaways:

Positive Insight:

<img width="896" height="637" alt="07_Positive Insight" src="https://github.com/user-attachments/assets/e5eb43ba-d592-4c6f-a9ab-d36f94819978" />


![08_Positive Insight Gif](https://github.com/user-attachments/assets/fd9ecd94-4655-4c9d-b9a7-a85fc1e546cf)


 

•	Getting customer in contract will defiantly make a huge difference in churn rate. If customer commit to stay longer with company then the company can save around 41% of churn revenue% 

 <img width="1309" height="736" alt="09_Positive Insight Pic" src="https://github.com/user-attachments/assets/24a098f6-99d2-4551-8a8a-82103a98a3c1" />


•	If Internet Type is  Fiber Optic, Customer status is 3.08 times more likely to be churned compare to other type of Internet.

<img width="1312" height="737" alt="10_Second Positive Insight" src="https://github.com/user-attachments/assets/1a829c1b-d1d0-4a94-8e36-80b841cf2306" />

 

Negative Insight:

<img width="886" height="671" alt="11_Negative Insight" src="https://github.com/user-attachments/assets/e4f5d126-43e0-4aa1-a1ba-f907ca23ebb4" />


![12_Negative Insight Gif](https://github.com/user-attachments/assets/d7723be6-3e19-40e4-8599-5251a0dcb7ce)




 

•	Month-to-Month contract shows no commitment from the customer which results in higher churn rate which is 50.3%.

 <img width="1309" height="733" alt="13_Negative Insight Pic" src="https://github.com/user-attachments/assets/0732fe93-277c-4f61-a6a3-de7cdc99052e" />


•	Month to Month contract  Fiber Optic churn rate is 60% compare to other Internet Service.

<img width="1313" height="746" alt="14_Second Negative Insight" src="https://github.com/user-attachments/assets/6e9a0ce2-d17c-4be0-aa0f-2d702aa21725" />

 

Suggestions/Recommendations:

•	Contract: Increase the number of contracted customer. Contract is key, try to get as much customer under contract as possible. The churn rate is much higher for people who have been with us for shorter period. Month-to Month churn customer status itself is 45.84%. We can create incentive plan for Yearly Contract, or Quarterly Contract. Incentives like additional Services(Streaming Security etc.) in a reduced rate may attract customer to get into contract.

•	Fiber Optic: Examine issues associated with the Fiber Optic Network to see if performance issues are resulting in poor customer experience. Offer customers Fiber Optic Internet with unlimited data and new device. As we can see customer stated competitor related reason for leaving , we need to make and extensive competitor analysis to understand what our competitor are doing better in terms of device and offers, especially for Fiber Optic. Fiber Optic churned customer status is 15% more than other Internet Types. Undertake a customer survey to identify the low customer satisfaction about internet service, Particularly the Fiber Optic and revise the plan to address the issue.

•	Service: Customer service plays a major role in retaining the customer , train employees to give the best customer service , Customer relation training for support persons and service providers. This would help save $580K churned due to stall attitude. Customer satisfaction is defined as customers being happy with a company's products, services, and capabilities. Customer's satisfaction is influenced by buyer experience. An excellent service exceeds consumer expectations and satisfaction by providing high-quality services.
It is Important that how quickly, effectively, and politely your customer service team deals with questions and issues. Make sure your team is properly trained to deal with every emotions of customer politely, competently, and quickly. And prepare them for dealing with your detractors, so that if they receive a call that points to the risk of churn they can act quickly and appropriately. Train them to empathize with the customer and reassure the cx that they are in good hands and there issues will be taken care.

•	Upsell, Cross-Sell, and Reward Your Customers

One of the major reasons for customer churn in telecoms is that customers find a better deal.

Make sure sales, marketing, and customer service teams know exactly what can we offer. This will help them to upsell and cross-sell products and services to the customers before they go looking for offers elsewhere. Research suggests that 40% of telecoms customers say they would have changed their mind if they’d been offered a better service plan.

Meanwhile, loyal customers should be rewarded, not penalized. Offer them exclusive discounts, deals, and opportunities to encourage them to stay.

<img width="717" height="365" alt="15_Recommendations" src="https://github.com/user-attachments/assets/b6435450-1565-4076-85a1-785b06ad22d2" />


 


