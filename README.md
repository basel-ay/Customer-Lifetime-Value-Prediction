# Customer-Lifetime-Value-Prediction

![image](https://github.com/basel-ay/Customer-Lifetime-Value-Prediction/assets/64821137/88e9133b-7a96-4af5-bfb9-7e558e29b5b8)

## What is Customer Lifetime value?
In marketing, customer lifetime value (CLV or often CLTV), lifetime customer value (LCV), or lifetime value (LTV) is a prediction of the net profit attributed to the entire future relationship with a customer. Customer lifetime value is a powerful piece of business intelligence that informs an efficient strategy for business growth.

## Why is Customer Lifetime Value Important?
* Customer Lifetime Value (CLV) helps you allocate your customer procurement budget based on what the new client will actually bring to your firm.

* CLV data helps build more accurate and detailed customer personas.

* To Learn the effect of certain high-level decisions on the value of customer assets. The CLV data can be used to encourage a company culture emphasizing long-term customer satisfaction, rather than solely focusing on short-term sales.

* You can calculate the profitability of a single customer.

## How machine learning helps?
Because of the importance of CLV, it is essential to know the future value of customers by looking at their historical transactions and hence look at the revenue of the organization as a whole. Machine Learning helps in bridging this gap by learning from historical data and predicting the following:

* The persona and the approximate Customer Lifetime Value of a new customer.

* Predicting the next transaction amounts and periodicity for existing customers, hence giving an indication of their adjusted CLV.

## **RFM** 

Stands for Recency - Frequency - Monetary Value. Theoretically, we will have segments like the below:

![image](https://github.com/basel-ay/Customer-Lifetime-Value-Prediction/assets/64821137/eac0f80a-6ac2-405f-8282-0186bbfa2729)

* Low Value: Customers who are less active than others, not very frequent buyer/visitor, and generates very low - zero - maybe negative revenue.

* Mid Value: In the middle of everything. Often using our platform (but not as much as our High Values), fairly frequently and generates moderate revenue.

* High Value: The group we don’t want to lose. High Revenue, Frequency, and low Inactivity.


As the methodology, we need to calculate Recency, Frequency, and Monetary Value (we will call it Revenue from now on) and apply unsupervised machine learning to identify different groups (clusters) for each.

## XGBoost

XGBoost (Extreme Gradient Boosting) is an advanced implementation of the gradient boosting algorithm. XGBoost has proved to be a highly effective ML algorithm, extensively used in machine learning competitions and hackathons. XGBoost has high predictive power and is almost 10 times faster than the other gradient-boosting techniques. It also includes a variety of regularization which reduces overfitting and improves overall performance. Hence it is also known as the ‘regularized boosting‘ technique.

When using gradient boosting for regression, the weak learners are regression trees, and each regression tree maps an input data point to one of its leafs that contains a continuous score. XGBoost minimizes a regularized (L1 and L2) objective function that combines a convex loss function (based on the difference between the predicted and target outputs) and a penalty term for model complexity (in other words, the regression tree functions). The training proceeds iteratively, adding new trees that predict the residuals or errors of prior trees that are then combined with previous trees to make the final prediction. It's called gradient boosting because it uses a gradient descent algorithm to minimize the loss when adding new models.

![image](https://github.com/basel-ay/Customer-Lifetime-Value-Prediction/assets/64821137/f3a4e25e-4108-4ce1-9471-ee9292df25b4)
