Project title: BUILDING-A-RETAIL-SALES-DATA-AGENT

Project objective:The goal of the project was to build a data agent on Databricks that allows business users, store managers, heads of departments, and executives to ask questions in plain language about retail sales performance and receive accurate data-backed answers without the need to write SQL code. 

Tools used: Platform - Databricks
            Language - SQL
            Documentation - Microsoft Word

Dataset overview: Column	Type	Description
Transaction ID	Bigint/integer	Unique identifiers for sales transactions
Date	Date	Date when the transaction occurred
Customer ID	String	Unique identifier for each customer
Gender	String	Gender of each customer
Age	Bigint/integer	Age of each customer
Product Category	String	Category of product purchased
Quantity	Bigint/integer 	Number of items purchased
Price per unit	Decimal/Bigint	Price per unit sold
Total Amount	Decimal/Bigint	Total value per transaction

Steps followed: 1. Upload dataset 
                2. Review columns 
                3. Prepare table 
                4.Create agent
                5.Write instructions
                6. Test 10 questions 
                7. Validate 3 answers 
                8. Write-up document 
                9.Push to GitHub 

Agent instructions: Your role is to be a retail sales analysis agent. Your job is to help business owners analyse data, by answering their questions that are related to: the total sales, customers, products, product_id, averages and trends and anything else related.

Your tone needs to be business professional, keep the responses short and informative. Use relevant numbers and percentages where necessary. If the question is unclear and or data is missing, ask for clarity and/ or for more information. If values are missing, clearly respond by saying that the value is missing and cannot be found in the dataset. Do not fabricate numbers and do not invent categories. Provide business recommendations where appropriate and provide recommendations where necessary. Make responses accurate and clear. Also, when asked to generate graphs, please do as requested with appropriate data and clear graphs with clear colours. 

Sample questions tested: 1.	Which product generated the highest total sales                                  amount? 
                         2.	Which product category is most popular among                                     customers who are below the age of 35 and are female?
                         3.	What is the total sales revenue generated?
                         4.	Which product has the lowest sales performance and                               what recommendation can you give to fix this? 
                         5.	Who is our best customer?
                         6.	Which month had the highest and Lowest sales?
                         7.	How are sales distributed across customer age groups?
                         8.	What percentage of total revenue comes from                                      transactions where more than 2 units were purchased?
                         9.	How does the average price per unit differ across                                the three product categories?
                         10.	How many male customers buy electronics?
                         
                         

Key insights:The store made $456 000 in total revenue. Across 1 000 transactions in 2023, the store made an average of about R456 per transaction. This helps measure future business performance. Electronics is the best and top-earning product category; there is not much of a big gap among the other products, and this shows that the business is performing well. We also see that female customers spend slightly more than male customers. Females spend $232 840 and Males spend $223 160.

Conclusion: The project delivered a working data agent capable of answering a range of business questions accurately. Writing the instructions from scratch was the most demanding part. I also struggled with reviewing the dataset using Run df.printSchema() and df.describe(). So, my alternative was to use the SELECT * function to view my dataset. I would validate more than three answers, ideally id validate all 10 answers because it builds greater confidence in the agent’s reliability.

Overall, this project showed me that building a data agent is not just a technical task. The thinking behind the instructions matters just as much as the setup and that is a skill that applies far beyond Databricks
