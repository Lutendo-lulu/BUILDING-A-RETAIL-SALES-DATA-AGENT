AI Retail Sales Analytics Agent using Databricks

Project Overview
This project demonstrates the development of an AI-powered Retail Sales Analytics Agent using Databricks and SQL. The agent enables business users to ask questions about retail sales performance in plain English and receive accurate, data-driven responses without writing SQL queries.
The solution is designed for executives, business owners, store managers, and department heads who need quick access to sales insights to support decision-making.


🎯 Project Objective
The objective of this project was to build a Retail Sales Analytics Agent capable of answering natural language questions related to sales performance, customer behaviour, product performance, and business trends.
The project demonstrates how AI can make business data more accessible to non-technical users by translating business questions into meaningful analytical insights.

🛠️ Technologies Used
Databricks
SQL
AI Data Agent
GitHub
Microsoft Word


📊 Dataset Overview
The dataset contains retail sales transactions completed during 2023.
Column	Description
Transaction ID	Unique identifier for each transaction
Date	Date of transaction
Customer ID	Unique customer identifier
Gender	Customer gender
Age	Customer age
Product Category	Product category purchased
Quantity	Number of items purchased
Price per Unit	Selling price per item
Total Amount	Total value of each transaction


⚙️ Project Workflow
The project was completed using the following process:
Uploaded the retail sales dataset into Databricks.
Reviewed and explored the dataset structure.
Prepared the SQL table for querying.
Built the Retail Sales Data Agent.
Designed detailed agent instructions.
Tested the agent using business-focused questions.
Validated the accuracy of selected responses.
Documented the project findings.
Published the project to GitHub.


🤖 Agent Design
The AI agent was designed to:
Answer retail sales questions using natural language.
Analyse sales, customers, products, and revenue.
Identify trends and business patterns.
Generate business recommendations.
Clearly communicate when information is unavailable.
Never fabricate values or create data that does not exist.
Respond professionally using concise business language.


💬 Sample Business Questions
The following questions were used to evaluate the agent:
Which product generated the highest total sales?
Which product category is most popular among female customers under 35?
What is the total sales revenue?
Which product has the lowest sales performance?
Who is the highest spending customer?
Which month recorded the highest and lowest sales?
How are sales distributed across customer age groups?
What percentage of revenue comes from purchases containing more than two items?
How does the average selling price differ across product categories?
How many male customers purchased electronics?


📈 Key Business Insights
The analysis produced several valuable business insights:
Total Revenue Generated: $456,000
Total Transactions Analysed: 1,000
Average Revenue per Transaction: $456
Electronics generated the highest overall revenue.
Sales across the remaining product categories were relatively balanced.
Female customers generated slightly higher total spending than male customers.
Female Revenue: $232,840
Male Revenue: $223,160
These insights can assist management in monitoring performance, understanding customer behaviour, and supporting future business decisions.


✅ Project Outcomes
The Retail Sales Analytics Agent successfully answered business questions using natural language while providing accurate, data-driven responses.
The project demonstrates how AI-powered analytics can improve accessibility to business information by allowing users to interact with data without requiring SQL knowledge.



⚠️ Challenges Encountered
One challenge involved exploring the dataset using Spark DataFrame functions. To efficiently inspect and validate the data, SQL queries were used to review the dataset before configuring the AI agent.
Another key challenge was designing effective agent instructions. Writing clear prompts was essential to ensure accurate, reliable, and business-focused responses.


📚 Lessons Learned
This project demonstrated that building an AI-powered data agent requires more than technical implementation.
The quality of the instructions provided to the agent significantly influences the quality of its responses. Effective prompt design, validation, and business understanding are all essential components of developing reliable AI analytics solutions.


🚀 Future Improvements
Future enhancements for this project include:
Validate every business question instead of a sample of three.
Connect the agent to live retail databases.
Integrate interactive dashboards for visual reporting.
Expand analytical capabilities with forecasting.
Deploy the solution as a web application for business users.


💼 Skills Demonstrated
SQL
Databricks
AI Agent Development
Prompt Engineering
Data Validation
Retail Sales Analytics
Business Intelligence
Data Analysis
Documentation
Problem Solving
