# Customer-Segmentation-Analysis

## Project Overview 
This project analyzes a bank’s customer data to gain insights into customer behavior, segment customers, and predict churn. The analysis includes calculating Customer Lifetime Value (CLV), conducting RFM (Recency, Frequency, Monetary) analysis, and identifying at-risk customers. The project also leverages clustering techniques to segment customers and visualizes various metrics to support business decision-making.

## Objectives

### Data Exploration:

- Load and inspect the dataset.
- Summarize basic information and statistics.
- Visualize key features such as age, credit score, balance, and tenure.

### RFM Analysis:

- Calculate Recency, Frequency, and Monetary scores for each customer.
- Segment customers into High, Medium, and Low Value categories based on RFM scores.
- Identify and display top high-value and low-value customers.

### Churn Analysis:

- Calculate and visualize churn rates by age group, gender, and geography.
- Identify at-risk customers and visualize their balance distribution.

### Customer Lifetime Value (CLV):

- Calculate CLV for each customer and visualize the distribution.
- Segment customers based on CLV and visualize the count of customers by CLV segment.

### Clustering Analysis:

- Apply **K-Means clustering** to segment customers based on credit score, age, balance, and estimated salary.
- Determine the optimal number of clusters using the **elbow method**.
- Visualize customer segments and cluster centers.

## Dataset
- Dataset Name: Churn_Modelling.csv
- Source: https://www.kaggle.com/datasets/marslinoedward/bank-customer-churn-prediction
   - Contains information on bank customers, including details such as credit score, age, balance, estimated salary, and churn status.
- Key Columns:
  - CreditScore: Customer's credit score.
  - Age: Customer's age.
  - Balance: Customer's account balance.
  - EstimatedSalary: Customer's estimated salary.
  - Exited: Indicates if the customer has churned (1) or not (0).

## Technologies Used
- Programming Language: Python
- Libraries:
  - Pandas for data manipulation and analysis
  - NumPy for numerical computations
  - Matplotlib and Seaborn for data visualization
  - **Scikit-learn** for machine learning and clustering


