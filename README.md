# Data Analytics for Business

### Topics Covered
- Core principles of the data analytics process
- Analytical techniques using Excel, including data transformation and visualisation
- Data manipulation and dashboard development using Tableau
- Relational database management, schema design, and ER modelling
- Data analysis using SQL
- Ethical frameworks in data analytics

#### *Grade: Distinction*


## Assignment Overview

This project involved acting as a data analyst for 2Market, a global supermarket operating both online and in-store. The objective was to gain deeper insights into customer purchasing behaviour through the analysis of sales, marketing, and advertising data. Specifically, the analysis focused on:
- Understanding customer demographics
- Identifying the most effective advertising channels
- Determining top-performing products and assessing whether sales patterns vary across different demographic groups

  
## Data Set
- marketing_data.csv *(Customer Information and Demographics / Sales Data / Marketing Data)*
- ad_data.csv *(Customer Information / Successful Lead Conversion)*

## Analytical Approach

In order to address the business questions, a structured analytical workflow was employed using Excel and SQL before finalizing data to be visualized via Tableau. First, the customer demographic data was cleaned to handle missing values, fix formatting issues, and standardize entries as needed. Initial data analysis was then performed to add an Age column and aggregate the average age of customers belonging
to each type of marital status and as well as their income brackets. This was particularly helpful in identifying and visualizing the relationships in the customer demographic to better understand the target audience.

SQL queries were then used to understand the structure of the data and interpret results to answer which products seem to sell best and whether or not that varies by customer demographics. The total spending per country, total spending per product per country, the most popular product in each country, and the most popular product based on marital status were all queried in SQL to generate results that helped gain further insight
on the current business scheme of 2Market. Consequently, SQL was also utilized to aid in understanding which is the most eJective method of advertising in each country. Appropriate SQL queries to LEFT join the customer demographic data and the advertising data were executed to aggregate functions to perform the necessary calculations which were in turn filtered and ranked by country, marital status, and platform to derive insights. All queries used aliases for clarity and the COALESCE function ensured that NULL “ad” conversion values were counted as zero. Thus, this SQL-driven analysis allowed for a detailed, structured foundation to inform eJective dashboard creation.

The Tableau dashboard was designed with clarity, interactivity, and stakeholder usability in consideration. It includes three main sections, with each aiming to provide analytical overview and answers to the business questions.

## Key Insights and Trends

- Married, high-income customers from Spain and Saudi Arabia are our most profitable segment. Targeting them with tailored campaigns could boost ROI significantly.

- In advertising, Instagram and Facebook stood out for high earners, whereas Bulkmail worked better for lower-income groups — this suggests a tiered ad strategy by income.

- Product-wise, Liquor and Non-Vegetarian items are top performers, especially in high-income regions. Meanwhile, Commodities and Chocolates performed well but varied more with income.


## Tableau Dashboard

<img width="637" height="357" alt="1" src="https://github.com/user-attachments/assets/b62e4bce-1b97-4006-89d0-b2c996d60434" />

<img width="638" height="359" alt="2" src="https://github.com/user-attachments/assets/cf140f5a-6dec-4dd5-92ee-7f04a75bb839" />

<img width="712" height="540" alt="image" src="https://github.com/user-attachments/assets/22a1f2b1-8d35-4d1c-a18d-7a2eeb2c3117" />

<img width="672" height="540" alt="image" src="https://github.com/user-attachments/assets/9ef6a521-e341-4091-917a-2c95a2bf2b27" />


## Strategic Recommendations

- Prioritize Spain and Saudi Arabia in future campaigns
- Focus marketing on married, high-income customers
- Use Instagram and Facebook for premium products, and Bulkmail for budget-oriented campaigns
- Promote Liquor and Non-Vegetarian items more prominently in high-value markets





