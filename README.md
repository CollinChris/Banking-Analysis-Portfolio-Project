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
![Image](https://github.com/user-attachments/assets/2f172cbf-d355-4779-a1bf-0129e5364c3e)
![Image](https://github.com/user-attachments/assets/08f61d8d-3e8d-42e6-95e1-f060abdcc48a)

### Python EDA Insights

- Step 5: Infer insights from created charts

![Image](https://github.com/user-attachments/assets/79da924a-63d1-4014-ba0a-50c0880ba21b)

### Power BI Dashboard creation

- Step 6 : Created measures for new features like Total Loans(Bank loans + Credit Card Balance + Business Lending) and Total Deposits(Bank Deposit + Savings Account + Foreign Currency Account +[Checking Accounts) for viewers to get an easier overview of past data.

![Image](https://github.com/user-attachments/assets/90858ee2-bf9a-44b1-b2c3-9fac9ac0279d)

- Step 7 : Create Home page to display quick overview of loans and deposits, and to show other pages.

![Image](https://github.com/user-attachments/assets/d7e2b908-c4c3-433b-b123-b79732424dcb)


- Step 8 : Create Loan Analysis page to show breakdown of which demographics/types of loans make-up the total loans

![Image](https://github.com/user-attachments/assets/0bf876af-1340-44e9-906d-123962901e62)

- Step 9 : Create Deposit Analysis page to show breakdown of which demographics/types of deposits make-up the total deposits

![Image](https://github.com/user-attachments/assets/73e2ef68-54a1-4cc8-8072-bc60c1843389)

- Step 10 : Extra page with all data to filter through for the backend if anyone requires specific information

![Image](https://github.com/user-attachments/assets/0ab5de94-a061-430b-ae5d-a18889b4c6b9)


# Insights & Possible Follow-Up Actions

## Insights 
### - Home Page

- Loan and Deposit Comparison – The total loans ($4.38bn) exceed the total deposits ($3.77bn), which suggests that business lending and personal loans are a significant revenue driver. Further analysis on loan repayment rates and risk exposure would be useful.Understanding customer behaviors around spending vs. saving could provide strategic insights for promotional offers or interest rate adjustments

- Business Lending Impact – The business lending value ($698.73M) accounts for a notable portion of the overall loan portfolio. Understanding sector-wise lending breakdowns could provide insights into risk diversification. 

### - Loan Analysis Page

- Checking vs. Savings Accounts Distribution – Checking accounts hold $158.19M, while savings accounts have a significantly lower balance of $4.39K. This suggests that customers prefer keeping their money in transactional accounts rather than long-term savings.

- Business Lending Relationship – A significant portion of funds ($698.73M) is allocated to business lending.


### - Deposit Analysis Page

- Foreign Currency Holdings – The foreign currency amount stands at $89.65M, suggesting a notable portion of deposits are held in non-local currencies, which could be influenced by international clients or forex investment strategies.

- Savings vs. Checking Accounts – Savings accounts hold $698.73M, while checking accounts have a higher balance of $963.28M. This indicates that customers prefer transactional accounts over long-term savings, which may require incentives to encourage higher savings retention.

- Income Band Deposit Distribution – Mid-income clients contribute the largest share of deposits ($1.09bn), followed by low-income ($0.5bn) and high-income ($0.42bn). This suggests that mid-income customers are the primary depositors, and targeted financial products could be designed for them.

- Engagement Timeframe Impact – Clients with under 20 years of engagement hold the highest deposits ($1.4bn), followed by  over 20 years ($1.1bn),  under 10 years ($0.8bn), and under 5 years ($0.4bn). This indicates that long-term clients contribute significantly to deposit stability.

- Nationality-Based Deposit Trends – European clients hold the highest deposits ($1.6bn), followed by Asian ($1.0bn), American ($0.6bn), Australian ($0.3bn), and African ($0.2bn). This suggests potential opportunities for region-specific banking strategies.


## Follow-Up Actions

- Deposit Growth Strategies – Develop initiatives to attract higher deposits, such as promotional rates or bundled financial products.

- Customer Segmentation – Analyze client demographics and transaction behaviors to optimize marketing strategies and engagement campaigns.

- Cross-Sell Opportunities – Encourage customers to open savings accounts or explore investment opportunities to increase portfolio diversification.

- Time-Based Comparisons – Implement a trend analysis over time to assess financial fluctuations and predict future growth

- Encouraging Long-Term Savings – Introduce higher-interest savings accounts or incentives to encourage customers to retain funds in savings rather than checking accounts.

- Deposit Retention Strategies – Identify patterns in deposit withdrawals and develop strategies to enhance stability, such as automatic savings plans or tiered interest rates.

- Liquidity Management Optimization – Align deposit growth with lending needs to ensure the bank maintains a strong financial position.

- Targeted Marketing Campaigns – Utilize demographic filters to create customized deposit promotions based on customer behaviors.

- Foreign Currency Deposit Optimization – Assess forex trends and offer competitive exchange rates or investment options for foreign currency holders.

- Income-Based Financial Products – Develop tailored banking solutions for mid-income depositors, such as flexible savings plans or investment portfolios.

- Client Retention Initiatives – Strengthen engagement with long-term clients through loyalty programs or exclusive banking benefits.

- Regional Banking Strategies – Expand services or marketing efforts based on nationality-based deposit trends to attract more deposits from underrepresented groups.

# Summary

- The dashboard created provides a deeper understanding of deposit behaviors, loan distributions, customer segmentation, and financial correlations using Power BI and Python-driven exploratory data analysis. 

- Key insights have revealed trends in savings, lending dynamics, client retention, and demographic influences, equipping financial decision-makers with actionable strategies to optimize banking products, mitigate risks, and enhance customer engagement.
- 
- By integrating structured follow-up actions, such as refining loan risk assessments, enhancing savings growth initiatives, and leveraging data-driven segmentation, this project establishes a valuable foundation for informed financial strategies, contributing to a more efficient and customer-centric banking ecosystem. 
