# Portfolios

### Table of Contents
* [Customer Behaviour Analysis](#CC)
* [Call Centre Churn & Diversity Inclusion Dataset](#Call_Centre)
* [ML Bootcamp Enrollment Predictions & Marketing Analysis](#Bootcamp_Enrollment)

### Customer Behaviour Analysis
Customer behaviour analysis helps to formulate data-driven decision-making for retail businesses. The primary objective is to develop a scalable data pipeline using cloud computing to conduct data ingestion, processing, and analysis with the Online Retail II dataset. 

The application will feature four analytical tasks, which consist of:
1. Customer Segmentation based on purchasing behaviour (Clustering)
2. Customer Lifetime Value Prediction (Regression)
3. Customer Churn Prediction (Classification)
4. Product Association Analysis (Association Rule Mining)

The dataset contains multiple tables, one from 2009 to 2010, and one from 2010 to 2011. The dataset is stored in HDFS supported by a cluster with 1 Name Node and 3 Data Nodes for reliability.

All analytical tasks are processed on a Spark Cluster with 1 Master and 2 Worker Nodes. 

For the development interface, Jupyter Notebook is used to execute PySpark code directly connected to the Spark Master. 

Overall, Docker, HDFS, Spark, PySpark, and MLib are used for machine learning in this project.

Data cleaning and preprocessing removed around 25,000 missing data points, and new features such as Recency, Frequency, and Monetary values were engineered onto each unique customer, which forms the foundation for the first three analytical tasks.

1. Firstly, **K-Means Clustering** algorithm segments customers into 5 different groups, including 'Consistent High Spenders' and a large group of 'Churned Customers', which the business should target for retention campaigns.
2. For **Customer Lifetime Value prediction**, Random Forest outperforms Linear Regression with a much lower Root Mean Squared Error. The most important predictor was the average quantity a customer buys.
3. For **Churn Classification**, Random Forest also outperforms Logistic Regression with an AUC of 0.80, and it also correctly identifies 83% of customers who are actually churned in the historical data. Businesses can utilise this method to identify churned customers.
4. Lastly, for **Product Association Rule Mining**, FP-Growth algorithm found strong rules. For example, customers who buy 'Poppy's Playhouse LivingRoom and Bedroom' are 93% likely to also buy the 'Poppy's Playhouse Kitchen'. Strong association rules like this are perfect for product bundling and recommendations to extend revenue.

### Call Centre Churn & Diversity Inclusion Dataset - Power BI

### ML Bootcamp Enrollment Predictions & Marketing Analysis
Predictive models with machine learning techniques were developed with existing and future data collected by the university to identify and predict students who would enrol on the bootcamp to reduce manual efforts and increase efficiencies in reaching out.

k-nearest neighbours algorithm (kNN), decision tree, and artificial neural network (ANN) are used. Based on the models developed, the decision tree not only has the highest accuracy but also possesses clear decision boundaries that allow us to pinpoint specific factors that influence enrollment decisions. 

The management can prioritise targeting students based on these factors to increase the chances of student recruitment with minimal labour and time spent contacting students. Leveraging insights provided by the model helps to personalise outreach and communication with prospective students to deliver appealing and high-quality pitches.
