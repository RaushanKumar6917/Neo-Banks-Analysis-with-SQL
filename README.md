# Neo-Banks-Analysis-with-SQL
[Case Study 3 Data Bank.docx](https://github.com/RaushanKumar6917/Neo-Banks-Analysis-with-SQL/files/14865521/Case.Study.3.Data.Bank.docx)


This repository contains scripts and queries for analyzing the Data Bank network, customer transactions, and business metrics using MySQL. The focus is on understanding the network infrastructure, customer distribution, transaction volumes, and average deposit behaviors to assist in business planning and growth strategies.

**Introduction**
Neo-Banks, operating solely online, are a recent development in the financial sector. The Data Bank project aims to bridge the gap between the digital world, new-age institutions, and cryptocurrencies by offering cloud data storage allotments related to account balances. This case study focuses on metrics calculations and smart data analysis to address challenges and plan for future growth.

**Schema Used**
The following schema is used for the Data Bank analysis:

regions: Contains information about different regions in the Data Bank network.

region_id: Unique identifier for the region.
region_name: Name of the region.
customer_transactions: Stores details of customer transactions.

customer_id: Unique identifier for the customer.
txn_date: Date of the transaction.
txn_type: Type of transaction (e.g., deposit, withdrawal).
txn_amount: Amount of the transaction.
customer_nodes: Represents the network nodes allocated to customers.

customer_id: Unique identifier for the customer.
region_id: Identifier for the region.
node_id: Identifier for the node.
start_date: Start date of node allocation.
end_date: End date of node allocation.
Case Study Questions
The repository addresses the following case study questions through SQL queries:

Nodes in Data Bank Network: Determine the number of different nodes in the Data Bank network.
Nodes in Each Region: Identify the number of nodes in each region.
Customer Distribution: Calculate the number of customers divided among the regions.
Total Transactions by Region: Determine the total amount of transactions for each region.
Average Node Migration Time: Calculate the average time taken to move clients to a new node.
Transaction Type Analysis: Determine the unique count and total amount for each transaction type.
Average Deposit Behavior: Analyze the average number and size of past deposits across all customers.
Monthly Customer Activity: For each month, identify the number of customers making more than one deposit and at least one purchase or withdrawal.
Execution
To execute the provided SQL queries, follow these steps:

Import the Data Bank dataset into your MySQL database.
Run the SQL scripts provided in this repository to analyze the data and derive insights.
Review the results generated by each query to understand the findings based on the case study questions.
Conclusion
Through the analysis of the Data Bank network and customer transactions, valuable insights can be obtained to optimize business strategies and plan for future growth. For detailed scripts and queries, please refer to the provided files in this repository.
