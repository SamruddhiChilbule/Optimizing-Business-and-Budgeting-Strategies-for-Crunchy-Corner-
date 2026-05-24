# Optimizing Business and Budgeting Strategies for Crunchy Corner 💸

<img width="1200" height="600" alt="unnamed" src="https://github.com/user-attachments/assets/040dca75-dbdc-4632-80bb-f24cd5fabd6f" />

## Introduction
Crunchy Corner, one of India’s largest fast-food restaurant chains, serves millions of customers daily across various cities with an impressive network of over 1,000 restaurants. Renowned for offering the largest SKU in the industry,
Crunchy Corner has become a household name for delicious and diverse food options. With such a massive operational scale, optimizing business and budgeting strategies is essential to maintain profitability, improve efficiency, and deliver 
exceptional value to its customers. 

In this project, we will explore Crunchy Corner’s data from 2020 to 2024, applying innovative approaches and data-driven insights to help the company overcome financial challenges, optimize operations, and achieve sustainable growth in a constantly evolving market.

## Flow of the Project
🔹Data Understanding

🔹Data Cleaning

🔹Data Modeling

🔹Data Analysis

🔹Uncover Insights

## Let’s understand the data

The Crunchy Corner Business data contains **47,7872 observations and 30 attributes**.

**The Data Dictionary is provided below —**
- **Year:** Financial years in which the business operations are recorded (2020 to 2024).
- **Quarter:** Financial quarters (Q1, Q2, Q3, Q4) used for quarterly analysis.
- **Month:** Financial months associated with sales and expenses.
- **Cluster Head:** Key management personnel overseeing operations in specific clusters.
- **SKU Code:** Unique identifier assigned to each product (SKU: Stock Keeping Unit).
- **SKU Description:** A detailed description of the product for identification.
- **Category:** The broad classification of products (e.g., beverages, snacks).
- **Sub Category:** Subdivision within a category (e.g., soft drinks under beverages).
- **Product:** Name of the primary product being sold.
- **Sub Product:** Specific product variations (e.g., flavors, sizes).
- **Channel:** The distribution medium to sell products (e.g., online, retail stores).
- **State:** Geographic states where the business operates.
- **Volume Mt:** Total quantity of SKU sold, measured in metric tons (Mt).
- **Gross Sales:** Total sales revenue generated before deductions like discounts and trade expenses.
- **Discount:** Total discount amount offered on products.
- **Trade Spend:** Funds allocated to trade promotions, such as price reductions or co-op advertising.
- **Total T & Disc:** The combined value of trade spend and discounts.
- **Net Revenue:** Revenue remaining after deducting trade spend and discounts from gross sales.
- **Raw Material:** Cost incurred for procuring raw materials required for production.
- **Packaging Material:** Expenses for packaging the products.
- **Industrial Fixed Cost:** Fixed business operational costs (e.g., rent, salaries)
- **Industrial Variable Cost:** Costs vary with production volume (e.g., utilities, direct labor).
- **COGS:** Cost of Goods Sold, which includes raw material and production costs.
- **Gross Profit:** The profit after deducting COGS from net revenue.
- **GP%:** Gross Profit as a percentage of net revenue, used to assess profitability.
- **Marketing:** Expenditure on marketing and promotional campaigns.
- **S&D:** Sales and distribution costs, including logistics and delivery expenses.
- **Depreciation:** Allocation of the cost of tangible assets over their useful life.
- **One-Off Item:** Exceptional or non-recurring expenses or income items.
- **Tax:** Taxes the business pays, such as income or sales tax.
- **Interest Income:** Income earned from investments or bank accounts.
- **Interest Expense:** Cost of interest paid on loans or borrowed capital.
- **Net Profit:** The final profit after deducting all expenses, taxes, and one-off items from gross profit.

## Model View in Power BI
For Crunchy Corner’s extensive dataset, consisting of 2 fact tables and 9 dimension tables, we have implemented the Snowflake Schema approach which is an effective model for organizing and analyzing large volumes of data.
<img width="992" height="782" alt="unnamed" src="https://github.com/user-attachments/assets/f61723e4-40ce-4719-89e2-7654eab95e1f" />

## Dashboard Preview
The end goal is to create a business solution report satisfying all the demands of the client. Here’s a glimpse of the final PowerBI Report.

As per the client’s demands and based on the acceptance criteria we have created Eight separate dashboards namely —

- Performance Analysis Dashboard
- Cost Analysis Dashboard
- SKU Level Turnover Dashboard
- Budgeting Analysis Dashboard
- Product Analysis Dashboard
- Quadrant Analysis Dashboard
- Pareto Analysis Dashboard
- Variance Analysis Dashboard

<img width="1200" height="697" alt="unnamed (1)" src="https://github.com/user-attachments/assets/42fd1cfd-5049-46ab-bccf-2b1810bdce91" />

<img width="1200" height="697" alt="unnamed (2)" src="https://github.com/user-attachments/assets/2a7e2853-e562-432a-b95d-c4c2e297dad2" />

<img width="1200" height="698" alt="unnamed (3)" src="https://github.com/user-attachments/assets/def98fd7-f7d1-48c6-8810-bfe9ccdab889" />

<img width="1200" height="701" alt="unnamed (4)" src="https://github.com/user-attachments/assets/4b878919-4595-4873-8653-077cf6a0c34b" />

<img width="1200" height="697" alt="unnamed (5)" src="https://github.com/user-attachments/assets/9569a33d-0e72-4aa2-9a18-3467de95cc5c" />

<img width="1200" height="698" alt="unnamed (6)" src="https://github.com/user-attachments/assets/b857a6af-83c0-4844-ab87-3d11f1057cbc" />

<img width="1200" height="697" alt="unnamed (7)" src="https://github.com/user-attachments/assets/d377edff-dfcd-451b-8dc0-f2044b3671b5" />

<img width="1200" height="697" alt="unnamed (8)" src="https://github.com/user-attachments/assets/7587f1f3-8dfc-4d4e-b1c5-a695658ae6d6" />

## Let’s dive deeper into analyzing the Crunchy Corner business -
First, let’s identify and analyze the key financial metrics essential for evaluating the overall business performance.

<img width="790" height="215" alt="image" src="https://github.com/user-attachments/assets/c2c1f18e-b21b-4d1f-97b8-c808056e921a" />

- **Total Number of SKUs (Stock Keeping Unit):** A unique code given to each product by businesses to help track inventory and manage orders. Crunchy Corner holds the distinction of having the largest SKU variety in the industry.

- **COGS(Cost of Goods Sold):** COGS represents the direct costs a company pays to make the products it sells, such as raw materials, labor, and production costs. It is subtracted from total sales to find out how much profit the company makes from selling its goods.

- **Gross Profit (GP):** Gross Profit is the money a company makes from selling its products after subtracting the cost of making those products (COGS). It shows how efficiently the company is producing and selling its goods. Gross Profit is calculated by subtracting the Cost of Goods Sold (COGS) from Net Revenue.

  **Formula**

  GP=Net Revenue−COGS

- **Net Revenue:** Net Revenue is the money a company keeps after subtracting costs like marketing, distribution, discounts, and other expenses from its total sales. It gives a clearer picture of the company’s real earnings, which can be used for operations, taxes, and profit.

**Note: Total revenue is not the same as Net revenue.**
- Total Revenue refers to the total amount of money a company earns from its sales before any deductions.
- Net Revenue is the amount remaining after subtracting different costs. It represents the actual revenue a company retains after these deductions.

- **EBITDA (Earnings Before Interest, Taxes, Depreciation, and Amortization):** EBITDA is derived by subtracting operating expenses (like selling, marketing, and administrative costs) from Gross Profit. It reflects the company’s profitability from its core operations, excluding non-operational and non-cash items.

  **Formula:**

  EBITDA=Gross Profit−Operating Expenses

- **PAT (Profit After Tax):** PAT is the final profit figure, showing the earnings available to the shareholders. It is derived by subtracting all non-operating expenses (such as taxes, interest, and depreciation) from EBITDA.

  **Formula:**

  PAT=EBITDA−Interest−Taxes−Depreciation and Amortization

- **Volume:** Volume refers to the total quantity of products sold or the amount of business activity carried out in a given period. In terms of sales, it indicates how many units of a product were sold, helping to assess market demand and business performance.

- **Raw Material Cost:** Raw Material Costs for Crunchy Corner include the expenses incurred in procuring the basic ingredients required for food preparation. This includes the cost of fresh produce, meats, packaging materials, spices, and other necessary raw materials to ensure high-quality meals are consistently served to customers.

- **Trade and Discount Cost:** Trade and Discount Cost refers to the financial outlay Crunchy Corner spends on promotional offers, discounts, and deals to attract customers or partners. This can include seasonal discounts, bundle offers, or loyalty incentives designed to boost sales and customer retention.

- **Marketing Cost:** Marketing Cost encompasses the expenses Crunchy Corner invests in advertising, brand promotions, digital campaigns, and other marketing activities aimed at raising brand awareness, reaching new customers, and retaining loyal ones. This could include social media ads, TV commercials, billboards, and promotional events.

- **Fixed and Variable Costs:**
    - Fixed Costs: These are the expenses that do not change regardless of the restaurant’s sales volume. For Crunchy Corner, fixed costs include rent for restaurant locations, salaries for management and permanent staff, and utility bills that are constant over time.
    - Variable Costs: These are expenses that fluctuate depending on the volume of sales. For Crunchy Corner, variable costs include raw materials, and transportation costs that vary based on the number of meals sold and orders processed.












