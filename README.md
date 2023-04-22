---
# Customer Profiling & Lifetime Value
---
## Authors
  1. Debanjan Saha (saha.deb@northeastern.edu)
  2. Ritika Rao (rao.rit@northeastern.edu)
  - Affiliation: College of Engineering, Northeastern University, Boston

---
## Data Description
In this project, we use a retail store data to determine the customer lifetime value and predict the churn using the customer demographics data.
The dataset in available online in [Kaggle](https://www.kaggle.com/datasets/darpan25bajaj/retail-case-study-data)

The dataset comprises of three files:
- Customer: Customer information including demographics
- Transaction: Transaction of customers
- Product Hierarchy: Product information

A detailed description of the data dictionary is mentioned in our project report.

---
## Video Presentation [Click on the Image Below]

[![image](https://user-images.githubusercontent.com/57592047/230706889-b3a03c49-7460-4c12-a017-b293321b4f31.png)](https://youtu.be/WMW35-JUdM8)

## Objective

We chose this dataset to handle the different prevalent scenarios that might considerably benefit holistic client profiling using Machine Learning in retail purchasing and marketing. In this project, we don't just develop one model with a specific goal in mind; instead, we look at numerous sorts of modeling and data mining techniques that can be performed using any transactional history dataset as well as customer demographic data. Customer demographics data is very sensitive for every organization because it contains a large amount of PII data. This is the only publically available dataset that provided us with all of the information we needed for our data mining problem. Our main goal was to make this project as much generalized as possible, and we aim to carry forward the learnings from this project into our future endeavors.


Using this data, we can perform various kinds of analysis such as:

- Time Series Analysis: Time series analysis can be performed on the transactions dataset to identify trends and patterns in customer purchases over time.

![image](https://user-images.githubusercontent.com/57592047/230707110-c6c11f37-3dd4-41a1-8d65-9352f271be71.png)

- Market Basket Analysis: Market basket analysis is a technique that analyzes customer transactions to determine which items are frequently purchased together. This can be visualized using association rule mining techniques such as Apriori algorithm. A network graph can be used to show the relationship between items.

![image](https://user-images.githubusercontent.com/57592047/230707141-09a0d4d5-4b78-4e74-b618-25f443d93001.png)


## Recency-Frequency-Monetary (RFM) Analysis

![image](https://user-images.githubusercontent.com/57592047/230707183-fb409421-cb0a-4553-82cb-ee2b11167039.png)

## Customer Profiling

- Customer Segmentation: Based on the customer demographics, purchase history and behavior, the customers can be segmented into different groups. This can be visualized using clustering techniques such as K-Means.

![image](https://user-images.githubusercontent.com/57592047/230707017-3186fb2a-1bbc-4a56-aa6a-58e467ff59f7.png)


- Customer Churn Analysis: Customer churn analysis can be performed to predict which customers are likely to leave the company. This can be visualized using decision tree algorithms and plotted on a bar chart to show the probability of customer churn.

- Customer Lifetime Value (CLV) Analysis: CLV is a prediction of the net profit attributed to the entire future relationship with a customer. This can be calculated by analyzing the customer's purchase history, behavior and demographics.

![image](https://user-images.githubusercontent.com/57592047/230706969-317b52b3-7c70-4726-b86e-c26c1d97cb4d.png)


---

All these experiments are conducted as part of the coursework project for IE 7275 - Data Mining under Prof. Sagar Kamarthi
