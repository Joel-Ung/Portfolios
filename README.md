# Portfolios

### Table of Contents
* [Customer Behaviour Analysis](#CC)
* [Superstore Marketing Campaign - SAS Curiosity Cup 2025](#IShowSAS)
* [ML Bootcamp Enrollment Predictions & Marketing Analysis](#Bootcamp_Enrollment)
* [Call Centre Churn & Diversity Inclusion Dataset](#Call_Centre)



### :walking: Customer Behaviour Analysis - Best Project Award 2025 (Type II - Big Data Query and Analytics)
Customer behaviour analysis helps to formulate data-driven decision-making for retail businesses. The primary objective is to develop a scalable data pipeline using cloud computing to conduct data ingestion, processing, and analysis with the Online Retail II dataset. Docker, HDFS, Spark, PySpark, and MLib are used for machine learning in this project.

1. Customer Segmentation based on purchasing behaviour (Clustering)
2. Customer Lifetime Value Prediction (Regression)
3. Customer Churn Prediction (Classification)
4. Product Association Analysis (Association Rule Mining)

Data cleaning and preprocessing removed around 25,000 missing data points, and new features such as Recency, Frequency, and Monetary values were engineered onto each unique customer, which forms the foundation for the first three analytical tasks.

1. Firstly, **K-Means Clustering** algorithm segments customers into 5 different groups, including 'Consistent High Spenders' and a large group of 'Churned Customers', which the business should target for retention campaigns.
2. For **Customer Lifetime Value prediction**, Random Forest outperforms Linear Regression with a much lower Root Mean Squared Error. The most important predictor was the average quantity a customer buys.
3. For **Churn Classification**, Random Forest also outperforms Logistic Regression with an AUC of 0.80, and it also correctly identifies 83% of customers who are actually churned in the historical data. Businesses can utilise this method to identify churned customers.
4. Lastly, for **Product Association Rule Mining**, FP-Growth algorithm found strong rules. For example, customers who buy 'Poppy's Playhouse LivingRoom and Bedroom' are 93% likely to also buy the 'Poppy's Playhouse Kitchen'. Strong association rules like this are perfect for product bundling and recommendations to extend revenue.

---

### :convenience_store: Superstore Marketing Campaign - SAS Curiosity Cup 2025

The reporting analysis presents the superstore's marketing strategy and focuses on the effectiveness of a campaign offering gold memberships, which provide a 20% discount on all
purchases. Using predictive modelling techniques, customer behaviours and preferences were analysed to determine the key factors influencing offer acceptance. 

The case study leverages data from past campaigns and applies machine learning techniques such as logistic regression, decision trees, and neural networks using SAS Enterprise Miner. Neural
Network is the most accurate predictive model and can be integrated into the superstore's marketing platform to identify customers likely to accept offers to increase the chances of successfully selling gold memberships.

---

### :tent: ML Bootcamp Enrollment Predictions & Marketing Analysis
Predictive models with machine learning techniques were developed with existing and future data collected by the university to identify and predict students who would enrol on the bootcamp to reduce manual efforts and increase efficiencies in reaching out.

k-nearest neighbours algorithm (kNN), decision tree, and artificial neural network (ANN) are used. Based on the models developed, the decision tree not only has the highest accuracy but also possesses clear decision boundaries that allow us to pinpoint specific factors that influence enrollment decisions. 

The management can prioritise targeting students based on these factors to increase the chances of student recruitment with minimal labour and time spent contacting students. Leveraging insights provided by the model helps to personalise outreach and communication with prospective students to deliver appealing and high-quality pitches.

---

### :telephone_receiver: Call Centre Churn & Diversity Inclusion Dataset - Power BI
A Call Centre becomes our client and requires a unified dashboard to review relevant Key Performance Indicators (KPIs)


