# Bank-Churn-Analysis
**Table of Content** 

[Problem Statement](https://github.com/OlajesuOgunyemi/Bank-Churn-Analysis#problem-statement)

[Project Objectives](https://github.com/OlajesuOgunyemi/Bank-Churn-Analysis/blob/main/README.md#project-objectives)

[Techniques Applied](https://github.com/OlajesuOgunyemi/Bank-Churn-Analysis?tab=readme-ov-file#techniques-applied)

[Dataset Description](https://github.com/OlajesuOgunyemi/Bank-Churn-Analysis/blob/main/README.md#dataset-description) 

[Project Analytical Questions](https://github.com/OlajesuOgunyemi/Bank-Churn-Analysis/blob/main/README.md#project-analytical-question-answered) 

[Project Visuals Implemented](https://github.com/OlajesuOgunyemi/Bank-Churn-Analysis/blob/main/README.md#project-visuals-implemented) 

[Project Key Insights](https://github.com/OlajesuOgunyemi/Bank-Churn-Analysis/blob/main/README.md#key-insights) 

[Challenges Faced](https://github.com/OlajesuOgunyemi/Bank-Churn-Analysis#challenges-faced)

[Lessons Learned](https://github.com/OlajesuOgunyemi/Bank-Churn-Analysis#lessons-learned)

[Project Recommendation](https://github.com/OlajesuOgunyemi/Bank-Churn-Analysis/blob/main/README.md#recommendation) 

[Portfolio Impact](https://github.com/OlajesuOgunyemi/Bank-Churn-Analysis/blob/main/README.md#portfolio-impact) 

[Conclusion](https://github.com/OlajesuOgunyemi/Bank-Churn-Analysis?tab=readme-ov-file#conclusion)



 ## Problem Statement:
Banks and financial institutions face a significant challenge in customer retention, with customer churn leading to loss of revenue and higher acquisition costs. The objective of this project is to analyze customer behavior using demographic, credit card usage, and account activity data in order to identify the key drivers of churn.

**By building a dashboard in Power BI, we aim to uncover insights into:**

Who the churned customers are,

What characteristics they share,

And how the bank can reduce churn by targeting at-risk customers through personalized strategies.

This analysis helps decision-makers understand patterns and trends behind customer churn, and enables data-driven interventions to improve customer loyalty and lifetime value.

 ### Project Objectives: 

This project helps the bank to identify patterns, understand the key factor behind why customers leave a retail bank(churn), and provide targeted, actionable recommendation to reduce customer attrition and improve retention 

 ## Techniques Applied
1. Microsoft Power BI
**Data Connection & Importing:**

Connected to a CSV/Excel file containing bank customer data.

Used Power Query to perform initial cleaning and transformation.

**Data Cleaning & Preparation (Power Query Editor):**

Removed unnecessary columns (e.g., IDs, inactive fields).

Handled null or missing values.

Standardized column names and formats.

Changed data types appropriately (e.g., date, numeric, categorical).

 **Presentation & Reporting**
 
**Dashboard Design:**

Created an interactive, single-page dashboard showing key insights.

Included filters for dynamic analysis.

Used color coding for better visual storytelling (e.g., red for churn).

**Export:**

Dashboard saved as .pbix file.

Screenshot taken for project documentation or GitHub upload.

 ## Dataset Description
 
 **-Source**: Bank Churn dataset (10,000 records), commonly used in industry case studies [Maven analytics website](https://mavenanalytics.io/data-playground?order=date_added%2Cdesc&search=bank%20churn)

 -**Key Features** 

        . Customer Id, Gender, Age, Geography 

        . Credit Score, Balance, Tenure, No of Product 

        . HasCrCard, Active Member, Estimated Salary, Existed Members 

         

  ### Project Analytical Question Answered

**1**  Which attribute (demographic or behavioral) are more common among churners vs Non churner

**2** What does the overall demographic profile of bank churners look like 

**3** Are there difference in account behavior based on geography? (e.g.. Churn rate by region) 

**4** What segment exist within the bank customer base, like age and credit score grouping and how did they how do they influence churn 

### Project Visuals Implemented

.Bar Chart 

.Stacked Column/Clustered Chart 

.Slicers 

.Matrix 

.KPI Card

 ### KEY INSIGHTS

**.Higher churn rate** :among customers aged 46-55  56-65 

**.Geographical Matters** : Certain countries (e.g Germany) showed higher churn rate 

**.Credit Score and Product Count** : Medium Credit Score combined with fewer bank product indicated a higher risk of churn 

**.Tenure** : Newer customer (less than 6 month) showed higher attrition 

## Challenges Faced:
 **Choosing the Right Visuals:**
Selecting the most effective visual representation for each metric was a challenge. It took several iterations to find the right balance between design and insight.

**Telling a Clear Story:**
Creating a story that communicates the insights clearly, especially for stakeholders unfamiliar with data, required careful layout, labeling, and use of interactive elements.

### RECOMMENDATION

**. Promote Product Bundling** : Encourage low product users to explore additional services 

**. Tailored Communication** : Customized offers and messaging based on customer profile 

**. Re-engagement Campaign** : For inactive members, incentivize activity to reduce churn risk 

**. Investigation** : Investigate the reason for lower churn in other geography (France, Spain) in order to increase the account behavior in the geography (country) 

**.Monitor and Re-evaluate** : Continue tracking churn metric monthly/quarterly after intervention 

**. Country Specific Initiative** : Focus retension effort where churn is highest 


  ## Lessons Learned:
**Data Cleaning Is Crucial:**
I realized how important it is to carefully clean and transform data before analysis. Handling null values, formatting inconsistencies, and understanding categorical variables (like “Attrition_Flag”) were key steps.

**Understanding Business Metrics:**
I learned how metrics like Total Transaction Amount, Credit Limit, and Customer Age can directly relate to churn behavior. This helped me improve my ability to translate data into meaningful insights.

**Visualization Matters:**
Using Power BI visuals such as pie charts, bar graphs, and slicers allowed me to make patterns in the data easy to understand, especially for non-technical stakeholders.

**Importance of Customer Retention:**
The project reinforced how valuable it is for businesses to not just gain customers, but to keep them — reducing churn saves cost and improves profitability in the long run.

 ## PORTFOLIO IMPACT

. Ability to handle real word banking data 

. Use of self service BI tools tools to surface valuable insights 

. Competence in translating data and visualization in strategic action  

. Ability to blend technical skills with business acumen  to reduce churn 

## Conclusion
The Bank Churn Analysis provided deep insight into the patterns that drive customer attrition. Customers who feel under-engaged or under-valued are most likely to leave. Through personalized engagement, better product exposure, and proactive communication, the bank can significantly reduce its churn rate and improve customer lifetime value.

 

 

 
