
**Detailed Analysis:**

**Data Preparation:**

Convert Data into a Table: Organize raw data into structured tables to make it easier to analyze in Power BI.

**Data Cleaning:**

Check for Zero and Blank Columns: Remove or handle columns with zero values or blanks to ensure data accuracy.

Remove Duplicates: Eliminate duplicate records to avoid skewed results.

Data Type Validation: Ensure each column has the correct data type (e.g., numeric, text, date) to facilitate accurate calculations and visualizations.

**Load Dataset into Power BI:**

Import the cleaned data into Power BI to start creating reports and visualizations.

**Adding Calculations and Columns:**

Conditional Columns: Create new conditional columns based on certain conditions to categorize or segment data. For example, you might create a column to flag high-value customers.

New Columns: Add columns for calculations not present in the original data. For example, calculating tenure in months from tenure in years.

**DAX Functions Used:**
ROUND,MAX,MIN,SUM,COUNT

**Geography Breakdown:**

**France:**

**Gender vs. Count of Credit Cards and Active Members:**

**Male:** 2753 Credit Cards, 2753 Active Members

**Female:** 2261 Credit Cards, 2261 Active Members

**Number of Products vs. Count of Gender:**

**1 Product:**

Male: 1398

Female: 1116

**2 Products:**

Male: 1296

Female: 1071

**3 Products:**

Male: 49

Female: 55

**4 Products:**

Male: 10

Female: 19

**Credit Score Status vs. Count of Credit Cards and Estimated Salary:**

**Excellent:**

Count: 35

Estimated Salary: RS 39,242,156.34

**Good:**

Count: 140

Estimated Salary: RS 174,133,270.09

**Poor:**

Count: 4839

Estimated Salary: RS 1,217,193,236.99

**Fair:**

Count: 0

Estimated Salary: RS 0

**Age Range vs. Count of Gender:**

**Adult:**

Male: 1842

Female: 1500

**Young:**

Male: 571

Female: 460

**Senior Citizen:**

Male: 340

Female: 301

**Summary Statistics:**

**Total Customers:** 5014

**Highest Credit Score:** 545k

**Lowest Credit Score:** 350

**Maximum Tenure:** 6 Years

**Minimum Tenure:** 1 Year 9 Months


**Germany:**

**Gender vs. Count of Credit Cards and Active Members:**

Male: 1316 Credit Cards, 1316 Active Members

Female: 1193 Credit Cards, 1193 Active Members

**Number of Products vs. Count of Gender:**

**1 Product:**

Male: 685

Female: 664

**2 Products:**

Male: 578

Female: 462

**3 Products:**

Male: 43

Female: 53

**4 Products:**

Male: 10

Female: 14

**Credit Score Status vs. Count of Credit Cards and Estimated Salary:**

**Excellent:**

Count: 22

Estimated Salary: RS 31,719,209.40

**Good:**

Count: 82

Estimated Salary: RS 281,056,674.92

**Poor:**

Count: 2404

Estimated Salary: RS 437,710,992.77

**Fair:**

Count: 1

Estimated Salary: RS 17,376.55

**Age Range vs. Count of Gender:**

**Adult:**

Male: 855

Female: 784

**Young:**

Male: 242

Female: 202

**Senior Citizen:**

Male: 189

Female: 207

**Summary Statistics:**

**Total Customers:** 2509

**Highest Credit Score:** 65k

**Lowest Credit Score:** 350

**Maximum Tenure:** 6 Years

**Minimum Tenure:** 1 Year 9 Months

**Spain:**

**Gender vs. Count of Credit Cards and Active Members:**

Male: 1388 Credit Cards, 1388 Active Members

Female: 1089 Credit Cards, 1089 Active Members

**Number of Products vs. Count of Gender:**

**1 Product:**

Male: 705

Female: 516

**2 Products:**

Male: 656

Female: 527

**3 Products:**

Male: 25

Female: 41

**4 Products:**

Male: 2

Female: 5

**Credit Score Status vs. Count of Credit Cards and Estimated Salary:**

**Excellent:**
Count: 20

Estimated Salary: RS 5,696,047.76

**Good:**

Count: 94

Estimated Salary: RS 110,270,939.70

**Poor:**

Count: 2363

Estimated Salary: RS 508,564,449.40

**Fair:**

Count: 0

Estimated Salary: RS 0

**Age Range vs. Count of Gender:**

**Adult:**

Male: 941

Female: 728

**Young:**

Male: 264

Female: 209

**Senior Citizen:**

Male: 183
Female: 152

**Summary Statistics:**

**Total Customers:** 2477

**Highest Credit Score**: 545k

**Lowest Credit Score:** 350

**Maximum Tenure:** 6 Years

**Minimum Tenure:** 1 Year 9 Months

**Insights:**

**Credit Score and Estimated Salary:**


**France** has the highest number of poor credit scores and a significantly higher total estimated salary for poor credit scores compared to Germany and Spain.

**Germany** shows the highest estimated salary for good credit scores, while **Spain** has the highest estimated salary for poor credit scores.

The fair credit score category shows no active members in France and Spain, suggesting possible issues with this classification.

**Age Range:**

**Adults** make up the majority of customers in all three countries, with a higher proportion in France and Spain compared to Germany.

The **Senior Citizen** category has a similar distribution across countries, with Spain and Germany showing slightly lower numbers compared to France.

**Number of Products:**

The majority of customers have 1 or 2 products across all geographies. France has the highest number of customers with 2 products, followed by Spain and Germany.

Customers with 3 or 4 products are a small fraction of the total.

**Gender Distribution:**

The number of male and female customers is fairly balanced across countries, but the distribution of products and credit scores varies.

**Recommendations:**

**Targeted Interventions:** For churn modeling, consider focusing on poor credit score customers, as they make up a large portion of the customer base in all countries.

**Product Offers:** Since most customers have 1 or 2 products, promotional offers for additional products might be effective.

**Regional Strategies:** Tailor strategies based on regional credit score trends and estimated salary differences.

**Customer Demographics:**

Males generally hold more credit cards and are more likely to have multiple products compared to females. This could indicate a need for targeted marketing or product offerings to address the gender disparity.

**Product Ownership Patterns:**
A significant number of customers have 1 or 2 products, with a sharp decline in those holding 3 or more products. Strategies to encourage more product adoption could be beneficial.
Credit Score Distribution:

The high prevalence of poor credit scores across all countries highlights a significant area of concern. This could inform risk management strategies and customer support initiatives to improve creditworthiness.

**Tenure and Credit Scores:**

The tenure and credit score data indicate that while some customers are long-term and potentially high-value, many others might be facing financial difficulties. Tailored retention strategies and financial advisory services could help manage churn and improve customer stability.
