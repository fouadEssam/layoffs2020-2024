# 📄 A brief introduction to the data

Title: "Layoff Analysis Project<br>
Description: The layoffs.xlsx file in the data directory contains the dataset used in this project.<br>
Columns:<br>
- Company: Name of the company experiencing layoffs.<br>
-	Location: Company location.<br>
-	Industry: Industry sector of the company (e.g., technology, finance, healthcare).<br>
-	Laid-Off Counts: Number of employees laid off.<br>
-	Date: Date the layoffs occurred.<br>
-	Stages: Each stage belongs to one of three categories: Early, Growth, or Exit stage.<br>
- Category:<br>
	Early Stage: Initial funding to develop the product and market strategy.<br>
	Exit Stage: The period after a company goes public and its shares are traded on stock exchanges.<br>
	Growth Stage: Subsequent rounds of funding to expand operations, enter new markets, and achieve growth milestones.<br>
---
# 🛠 Used Tools
I used SQL to gather data from flat files,  make preparations and perform manipulations. Then, I used Power BI to visualize the data and add some analysis

The sequence of my project:<br>
![image](https://github.com/user-attachments/assets/c16ef33f-dc0a-4282-aea7-dd98736ea7a7)

 
Based on these steps, we perform our project:
1.	Business Question: We start by defining the questions we want to answer through insights. Examples of such questions include:
- Top 10 countries by layoff count and top industries with the highest layoffs.
-	Average layoffs count by year
-	identify which stage has the highest likelihood of layoffs. Comparison between Profit and Budget for Each Movie
2.	Is there a relationship between layoffs and increased funding? 
3.	Get Data: We obtain the necessary data from Kaggle 
4.	Explore Data: In this step, we display the data's information and columns, and search for null values to ensure the quality of our data.
5.	Prepare Data:
-	 We clean and transform the data to make it suitable for analysis. This includes:
-	Handling missing values (e.g., imputation or removal)
- We aim to retain as much information as possible by filling null values in important columns with minimum values. We choose minimum values because nulls might indicate that no layoffs occurred in that country or there were no increases in funding.<br>
 ![image](https://github.com/user-attachments/assets/77dab783-323e-499b-8269-baea13eb5e06) <br>
![image](https://github.com/user-attachments/assets/02c69b6b-fc8e-4797-9a57-e0c478a180fe) <br>

-	Removing duplicates <br>
  ![image](https://github.com/user-attachments/assets/be162cca-b02f-4587-9d44-f272a07f4a23) <br>

 -	Correcting inconsistencies (e.g., standardizing formats)<<br>
![image](https://github.com/user-attachments/assets/1b9a492d-f899-4906-a473-3418dc12ad7f)

 
6.	Analyze Data: We apply statistical methods to extract insights and answer the business questions. This can involve:
---
# 🧮 Some insights
6.1	Descriptive statistics<br>
 ![image](https://github.com/user-attachments/assets/304b0c5e-3c55-4601-b02e-b1b0a01481c0)<br>

6.2	Data visualization  : In this stage we connect to Power BI by navigating to Home >> Get Data >> SQL Server. This feature allows us to import data from a SQL Sever.

- Despite the media sector experiencing the most significant increase in funding, it did not have the highest number of layoffs. This indicates that there is no correlation between increased funding and the number of layoffs. In fact, the retail sector had the highest number of layoffs.<br>
![image](https://github.com/user-attachments/assets/0f84a692-4134-4442-96bd-85258d85fbfd)<br>
- And the USA had the highest number of layoffs.<br>
![image](https://github.com/user-attachments/assets/68b9306d-cb20-4be3-bae1-8cee6db224a5)<br>
- An interesting insight is that the highest number of layoffs occurred during the exit stage of the company.<br>
![image](https://github.com/user-attachments/assets/32a49de7-39a7-4b4d-897f-61ebf461ff50)<br>.
- In my opinion, one of the most useful KPIs is the one that represents total funds and total layoffs based on our selection. We can also choose the period, whether it’s 1 week, 1 month, 1 year, or all periods. Additionally, it shows the difference that occurs if it increases or decreases compared to the last period.<br>

![image](https://github.com/user-attachments/assets/23d551dc-94ba-4a73-b3d8-b75a40c9eb9f)<br>
![image](https://github.com/user-attachments/assets/dbd96f20-bb46-4c98-8d5b-90caf969e3b1)<br>

# 📊 Dashboard
7.	Present Findings: Finally, we communicate the results of our analysis through reports, dashboards, or presentations. This step is crucial for making data-driven decisions.<br>
![image](https://github.com/user-attachments/assets/2ee0c3be-d0d6-435c-93f0-8ebb431259a8)


