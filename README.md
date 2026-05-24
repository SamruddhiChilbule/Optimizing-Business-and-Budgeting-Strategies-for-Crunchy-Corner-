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
    - **Fixed Costs:** These are the expenses that do not change regardless of the restaurant’s sales volume. For Crunchy Corner, fixed costs include rent for restaurant locations, salaries for management and permanent staff, and utility bills that are constant over time.
    - **Variable Costs:** These are expenses that fluctuate depending on the volume of sales. For Crunchy Corner, variable costs include raw materials, and transportation costs that vary based on the number of meals sold and orders processed.

- **General and Administrative Costs:** General and Administrative (G&A) Costs for Crunchy Corner involve overhead expenses necessary for running the business. These costs include office expenses, salaries for corporate staff, legal fees, insurance, and other administrative functions that support the overall operations of the company but are not directly tied to food production or sales.

- **Sales and Distribution Costs:** Sales and Distribution Costs include the expenses incurred in delivering products to customers and managing sales. This includes the costs of transportation, delivery services, and the expenses related to running the sales process at each restaurant. These costs ensure that products are efficiently distributed to meet customer demand.

## Now that we’ve covered the key metrics, let’s dive into the year-wise analysis of net revenue from the financial year 2020 to 2024.
Let’s First analyze in which year, quarter, and month, the company generated the highest Net Revenue.

<img width="1200" height="593" alt="unnamed (9)" src="https://github.com/user-attachments/assets/07d3cbad-c4a6-40cc-bad0-2616fa8e983e" />

**_The highest Net Revenue was recorded in the financial year 2023._**

<img width="1200" height="594" alt="unnamed (10)" src="https://github.com/user-attachments/assets/fddb5f69-919f-40cd-a0e4-d874d7761dde" />

_**On analyzing the quarterly Net Revenue for 2023, it is clear that the company reached its peak revenue of 30.8M in Quarter 3.**_

<img width="1200" height="593" alt="unnamed (11)" src="https://github.com/user-attachments/assets/c39face9-eb9b-4bec-8ab6-7fbc1e5b3d0d" />

_**Within Quarter 3, the month of August stood out, achieving the highest Net Revenue of 12.4M.**_

<img width="1200" height="593" alt="unnamed (12)" src="https://github.com/user-attachments/assets/a585a07b-2ff7-42aa-8f7e-a01705d7ec4f" />

_**This is the month-wise Net Revenue for the year 2023.**_

Next, let’s examine the Net Revenue across all years and the year-over-year (YOY) Net Revenue of the company.

<img width="388" height="351" alt="image" src="https://github.com/user-attachments/assets/9fed70c1-3080-4c0c-bdf0-5afcd6fbc469" />

Similarly, let’s visualize the quarterly Net Revenue from the financial year 2020 to 2024.

<img width="422" height="687" alt="image" src="https://github.com/user-attachments/assets/5f68ca8e-b5ec-4a2a-a82d-a2488c016570" />

Below is the visualization chart for the Income Statement Flow from Net Revenue (NR) to Profit After Tax (PAT). This flow outlines how a company’s revenue is transformed into its final profit through the subtraction of various costs and expenses at different levels.

<img width="1200" height="458" alt="unnamed (13)" src="https://github.com/user-attachments/assets/03a8dbe7-61ca-4e74-bd05-0ffa4c20f811" />

Crunchy Corner operates across seven states in India, including Uttar Pradesh (UP), Maharashtra (MH), Gujarat (GUJ), Karnataka, West Bengal (Calcutta), and Tamil Nadu. Let’s delve into the state-wise Net Revenue contribution to understand how each region drives the company’s overall performance.

<img width="1200" height="617" alt="unnamed (14)" src="https://github.com/user-attachments/assets/155c9089-fb08-4ba4-be41-a3d047de0c1e" />

_**Observations reveal that Uttar Pradesh (UP) contributes the highest Net Revenue of 193.33M, while Tamil Nadu records the lowest Net Revenue contribution of 3.72M among all the states where Crunchy Corner operates.**_

Now, let’s examine the Income Statement Flow from Net Revenue (NR) to Profit After Tax (PAT) at the state level to understand the financial performance and profitability of each region.

<img width="1200" height="467" alt="unnamed (15)" src="https://github.com/user-attachments/assets/04bedbfc-d729-49b9-ab48-e6409f2d5578" />

Crunchy Corner utilizes nine distinct distribution channels to sell its products: Direct Sales, Bulk Sales, Culinary Service, Distributor, External Sales, Domestic Sales, Online Sales, Others, and MFG Sales. Let’s identify which distribution channel contributes the highest Net Revenue.

<img width="1200" height="612" alt="unnamed (16)" src="https://github.com/user-attachments/assets/2f45f40b-f96c-4206-8d19-cd7795db1fe3" />

_**As observed, Direct Sales contribute the most to the Net Revenue, followed closely by Bulk Sales.**_

Crunchy Corner, being a large fast-food distribution chain, assigns Cluster Heads to manage and oversee operations across different regions, ensuring efficient business functioning and optimized performance. Let’s now analyze the Net Revenue by Cluster Heads to gain valuable insights into Crunchy Corner’s overall performance under each cluster head.

<img width="1200" height="538" alt="unnamed (17)" src="https://github.com/user-attachments/assets/5b04f8ef-3ba0-495e-8bb0-10310fa0a47d" />

**_It appears that under Cluster Head Umar, the highest Net Revenue is being generated, indicating strong performance and efficient management strategies being implemented by Umar._**

As Crunchy Corner is a renowned fast-food restaurant chain with the largest SKU base in the industry, it offers products across nine different categories. Let’s now analyze the Net Revenue by SKU category to understand which categories contribute the most to the company’s overall revenue.

<img width="1200" height="537" alt="unnamed (18)" src="https://github.com/user-attachments/assets/2786b11b-dad5-4979-86fa-63fe177a98a3" />

_**As observed, the Protein Pack category generates the highest Net Revenue, followed by Fresh Fare and Country Fries, contributing significantly to Crunchy Corner’s overall revenue.**_

Now, let’s examine the Income Statement Flow from Net Revenue (NR) to Profit After Tax (PAT) at the Category level to understand the financial performance and profitability of each category.

<img width="1200" height="465" alt="unnamed (19)" src="https://github.com/user-attachments/assets/14789bdc-d36f-4650-9d12-b1d1e0a5407f" />

Now that we’ve completed the analysis of Crunchy Corner’s overall performance, let’s dive deeper into the cost analysis. By examining various costs such as raw material costs, marketing expenses, sales and distribution costs, and fixed and variable costs, we can gain a clearer understanding of the factors impacting profitability. This will allow us to identify areas for cost optimization, improve operational efficiency, and develop strategies to enhance overall financial performance in the long term.

Below is the Cost Analysis Funnel Chart, which visualizes the various costs incurred by Crunchy Corner. The chart breaks down key cost categories, providing a clear view of how expenses.

<img width="1200" height="586" alt="unnamed (20)" src="https://github.com/user-attachments/assets/7b33a4ae-ee18-4bfa-9fdf-8b0564e8dd4a" />

Below is the chart for Marketing Costs by Category, providing a breakdown of the marketing expenses allocated to each product category.

<img width="1200" height="601" alt="unnamed (21)" src="https://github.com/user-attachments/assets/06a069c2-33ca-4251-8ef8-4d6254b51a8b" />

**As we can observe, the top-performing category, Protein Pack, is also responsible for generating the highest marketing cost, which is in line with the increased efforts to promote and drive sales in this high-revenue category.**

_**In the Cost Analysis Funnel, we observed that Raw Material Costs account for the highest percentage of total costs. To better understand its impact on Crunchy Corner’s profitability, let’s take a deeper dive into the Raw Material Cost.**_

<img width="1200" height="465" alt="unnamed (23)" src="https://github.com/user-attachments/assets/23bc4b1b-3a04-4173-afc2-e26fb7b35529" />

_**The Raw Material Cost Represented by the line chart, shows slight fluctuations. The peak occurs in 2023, indicating the highest raw material cost during this period.**_

_**In 2024, there is a visible decline in raw material costs compared to 2023, which might reflect better cost control or reduced material requirements.**_

In this problem statement, we are provided with both actual data and the target/budget of the company. This dual dataset allows us to compare and evaluate the company’s performance against the set goals, identifying any variances. Let’s deep dive into it —

Firstly, let’s analyze YOY Net Revenue for both actual and budget data

<img width="1200" height="463" alt="unnamed (24)" src="https://github.com/user-attachments/assets/b64fe387-ae83-4e90-a8d0-cf7e96992b52" />

- **NR** — Net Revenue (Actual)
- **B NR** — Net Revenue (Budget)
- **YOY NR B%** — YOY NR % (Budget)

**_In 2021 and 2022, the actual NR is closer to the budget, reflecting better alignment with financial projections._**

**_In 2023, actual NR not only fails to meet the budget but also reflects a dip in performance, as shown by the steep YoY decline._**

**_2024 continues to show a gap, but the negative YoY change indicates a gradual performance improvement._**

Now, let’s analyze and compare the Year-over-Year (YoY) Net Revenue for actual and budgeted data across categories.

<img width="1200" height="466" alt="unnamed (25)" src="https://github.com/user-attachments/assets/e518e123-52a6-4703-8582-7bc53eb3922f" />

_**Protein Pack is the highest revenue generating category with Actual NR at 221M and Budgeted NR at 259M. However, there is a significant -14.42% YoY decline in Budgeted NR, indicating potential challenges in sustaining growth.**_

_**Fresh Fare and Country Fries categories exhibit modest revenue levels (82M and 76M, respectively), and their YoY Budget NR % indicates steady growth (+8.57% and +11.81%, respectively).**_

_**Cake and Sweet Crust categories exhibit the lowest net revenue levels with declining YoY Budget percentages of -14.28% and -9.87%, respectively.**_

Next, I am going to perform a PVM (Price, Volume, Mix) Analysis. It is a method used to analyze and understand the changes in a company’s revenue and profitability by breaking down the effects of three key factors:

**- Price:** Analyzing how changes in the price of different products (SKUs) affect the overall Net Revenue. This helps in understanding the revenue generated from price adjustments across various product categories.

**- Volume:** The volume effect looks at how changes in the number of units sold affect revenue.

**- Mix:** The mixing effect examines how the combination of different products sold influences revenue.

PVM is essential for businesses that want to dig deeper into their sales data. By understanding these three effects, companies can make better decisions. They can see if they need to adjust prices, boost sales volume, or change their product mix.

<img width="1200" height="592" alt="unnamed (26)" src="https://github.com/user-attachments/assets/9b882243-a2af-40b8-b3a6-0ed3952aa3ae" />

### Thank You for Reading!!


















