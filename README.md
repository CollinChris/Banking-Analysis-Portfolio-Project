Banking Analysis Portfolio Project

An Analysis of banking Data (SQL, Python, Power BI)
# Banking Analysis

![Image](https://github.com/user-attachments/assets/b71883b0-d92e-4b9d-ae95-996e8ea8804c)

### Power BI Dashboard
The Power BI file is included in this Github repository, currently I am using a free version of Power BI so cannot upload it as a link.

## Content

- Problem Statement
- Steps followed
- Insights & Possible Follow-up Actions(Python & Power BI)
- Summary

## Problem Statement

The banking sector relies heavily on data-driven insights to enhance customer experience, optimize financial offerings, and manage risk. 

With the large amount of data, this project aims to analyze the dataset to find meaningful patterns and actionable insights to help improve decision-making that might help client segmentation, loyalty programs, fee structures, credit risks assessments, and predict insights.

### Steps to complete
1. Load dataset into SQL server
2. Connect SQL server to Python Jupyter Notebook for EDA(exploratory data analysis)
3. Visualize the data for analysis and easier readability for business owners(Power BI)
4. Interpret the results

### Steps followed 

- Step 1 : Load the dataset from a CSV file to MySQL Workbench to connect to Python

![Image](https://github.com/user-attachments/assets/a749e328-c07e-4d04-a0b8-2875903359fb)

### Python EDA(Exploratory Data Analysis)
(Jupyter Notebook file is attached in this repository if needed for reference)

- Step 2 : Connect to SQL Server and begin data exploration

![Image](https://github.com/user-attachments/assets/5158089e-de31-4458-8b0f-565e625ceaaa)

- Step 3 : Check for missing data and begin data preprocessing(In this case, organising features into numerical categories and creating sections for income bands)

![Image](https://github.com/user-attachments/assets/e03dc252-9c73-4717-a97c-5f54c4d8b3ad)

- Step 4 : Create charts(for univariate, bivariate, and multivariate analysis) to analyze for any patterns/relationships in the dataset

![Image](https://github.com/user-attachments/assets/95853f0f-33fe-42bc-893d-6d35ecc47c02)
![Image](https://github.com/user-attachments/assets/e6bf129b-8f8f-4068-a986-e9bb22a7e769)
![Image](https://github.com/user-attachments/assets/fd1a68e5-7310-4d6c-811f-b564d37e9b90)
![Image](https://github.com/user-attachments/assets/08f61d8d-3e8d-42e6-95e1-f060abdcc48a)

- Step 5: Infer insights from created charts

### Python EDA Insights

![Image](https://github.com/user-attachments/assets/79da924a-63d1-4014-ba0a-50c0880ba21b)

### Power BI Dashboard creation

- Step 6 : Create pivot tables to prepare data for visualization.



- Step 7 : Pick and test visualizations for our dashboard to consider what can provide the most value to our users. 


- Step 8 : Loaded the Excel dataset connected from the SQL queried database.

- Step 9 : Created similiar charts to the Excel with more visual formatting.




# Insights & Possible Follow-Up Actions

- 2018 had a significant drop in sales after April, resulting in the least profitable year so far, further analysis is required to find out the reason for such a drastic reduction in sales(for example, failed marketing campaigns, loss of certain sales reps, etc)



- Baldwin Bikes is consistently the highest in sales each year, we may want to do a further comparison of how they run differently from the other stores to see if any strategies can be implemented to help the profitability of other stores. 


- Mountain bikes have most of the share of sales and electric bikes are the least, depending on what direction the business decides, we can either provide a stronger marketing strategy for electric bikes or continue focusing on mountain bikes.



- New York has the highest sales for bikes, we can do further analysis to find out why. Whether it's a specific demographic in New York that is more present so we can do targeted marketing in other regions, or it's just New York is more bike friendly so can decide on other strategies moving forward.



- By identifying the top customers, we can do an analysis of the demographics of top bike purchasers to create targeted marketing strategies and conduct targeted surveys to find out why they are willing to spend more on bikes.


- Marcelene Boyer & Venita Daniel are the top 2 leading sales reps by a significant margin, so the company should provide incentives for them to stay and share their sales strategies to the rest of the team.


# Summary

- From the insights above, it can be shown how the dashboard can be used to find further insights for the users/business, and depending on which direction to stakeholders decide to go, we can use the relationships between the data to do further analysis to suggest the best courses of action and form business strategies.
