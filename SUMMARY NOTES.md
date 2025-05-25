
# Summary Notes for Excel & Python Project
This project demonstrates an integrated workflow combining Microsoft Excel and Python for complete business data analysis. Excel served as a foundational tool for structured reporting and dashboarding, while Python was used for advanced computation, visualizations, and interactivity. Below is a summary of each dataset analyzed, insights gained, and actions recommended based on the results.

## 1. EMPLOYEE DATASET
**Excel Work:**
- Cleaned formatting issues and removed incomplete rows.
- Used pivot tables to calculate average salary by role and department.
- Conditional formatting flagged outliers in compensation patterns.

**Python Workflow:**
- Cleaned and converted data types using `pandas`.
- Visualized average salary by role with `seaborn.barplot()` using `numpy.mean`.
- Created an interactive scatter plot using `plotly.express.scatter()` showing experience vs. salary colored by department.

**Insights:**
- A clear correlation exists between years of experience and salary.
- Consultants and Analysts earned above-average compensation.
- Some Coordinators had unusually high salaries for the role.

**Suggested Actions:**
- Review salary bands across roles to address inconsistencies.
- Conduct job level audits for the Coordinator title to ensure consistent compensation.
- Use these insights to inform future HR and compensation strategies.

## 2. SALARY BY ROLE
**Excel Work:**
- Summarized total salary by role using pivot tables.
- Ranked roles by salary allocation.

**Insights:**
- Analysts and Consultants account for the largest share of total salary expenditure.
- Indicates either higher headcount or compensation within these roles.

**Suggested Actions:**
- Analyze headcount distribution to confirm whether compensation or staffing is driving salary cost.
- Consider workforce balancing if one role is overrepresented or overpaid.

## 3. AD BUDGET VS SALES
**Excel Work:**
- Cleaned budget and sales data.
- Calculated ROI manually and used column charts to compare performance.

**Python Workflow:**
- Computed ROI using Pandas and visualized top 10 companies with highest ROI using `matplotlib.pyplot`.
- Created a regression scatter plot with `plotly.express` to explore the relationship between ad spend and sales.

**Insights:**
- Sony Inc. and Toyota Inc. achieved the highest ROI.
- Linear relationship identified between Ad Budget and Sales.

**Suggested Actions:**
- Allocate more ad spend to high-performing companies or replicate their strategies across others.
- Use ROI benchmarks to optimize future budget distribution.
- Refine regression models to forecast future campaign effectiveness.

## 4. LOANS AND INTEREST
**Excel Work:**
- Calculated interest and total repayment amounts.
- Used charts to visualize repayment trends.

**Python Workflow:**
- Added a calculated column for Total Repayment.
- Plotted interest rate distribution using `seaborn.histplot`.
- Used `plotly.express.box` to compare repayments across different loan durations.

**Insights:**
- Higher interest rates significantly impact total repayment.
- Long-term loans showed wider repayment ranges, often due to larger principals or higher rates.

**Suggested Actions:**
- Adjust lending guidelines for long-term loans to reduce risk of default.
- Provide rate transparency and repayment projections to clients.
- Use repayment data to develop risk-based pricing models.

## 5. PRICE DISCOUNT
**Excel Work:**
- Modeled revenue before and after discount.
- Used conditional formatting to flag high-loss products.

**Python Workflow:**
- Calculated revenue loss due to discounts.
- Visualized product-level impact using `seaborn.barplot`.

**Insights:**
- Significant revenue loss observed for high-discount, high-volume products.
- Discounts beyond 25% had diminishing returns.

**Suggested Actions:**
- Cap discount levels for certain SKUs or customer segments.
- Use historical discount data to refine promotional strategies.
- Conduct A/B testing on discount rates to maximize revenue retention.

## 6. PIVOT TABLE VALUES
**Excel Work:**
- Created pivot tables by category and product.
- Summarized total sales and net revenue.

**Insights:**
- Food & Beverage products were top contributors to revenue volume.
- Automotive products had higher unit value but lower frequency.

**Suggested Actions:**
- Focus marketing on volume-driven categories.
- Promote high-margin products with targeted ads.
- Evaluate bundling or upselling strategies for lower-frequency items.

## 7. RANGE LOOKUP (GRADING)
**Excel Work:**
- Built a lookup system to assign grades based on score.
- Used `VLOOKUP` and `IF` functions for automation.

**Insights:**
- Scores were accurately graded based on a consistent threshold scale.
- Grade assignment logic proved reliable across multiple entries.

**Suggested Actions:**
- Use this grading template as a foundation for broader performance evaluation systems.
- Extend logic to employee evaluations, training assessments, or customer feedback scoring.

## Tools and Techniques Used
**Excel:**
- Data Cleaning: Manual corrections, formatting, validation
- Analysis: PivotTables, Formulas (`IF`, `VLOOKUP`, `SUMIFS`)
- Visualization: Column and pie charts, conditional formatting
- Dashboarding: KPI views, slicers, dynamic tables

**Python:**
- `pandas` – Data manipulation, column calculations
- `matplotlib.pyplot` – Static plots for publication
- `seaborn` – Enhanced statistical visualizations
- `numpy` – Aggregations and mean estimators
- `plotly.express` – Interactive browser-based visualizations

## Visual Outputs
| Output Description                     | File Name                   |
|----------------------------------------|-----------------------------|
| Average Salary by Role                 | avg_salary_by_role.png      |
| Experience vs Salary (Interactive)     | exp_vs_salary.html          |
| Top Companies by ROI                   | top_roi_companies.png       |
| Ad Budget vs Sales (Regression)        | budget_vs_sales.html        |
| Interest Rate Distribution             | interest_rate_dist.png      |
| Repayment by Loan Term (Box Plot)      | repayment_by_term.html      |
| Revenue Loss Due to Discounts          | discount_impact.png         |

## Final Thoughts
This project demonstrates the combined strengths of Excel and Python in a real-world analytics workflow. Excel provides structure, accessibility, and stakeholder clarity, while Python scales the analysis with reproducibility, interactivity, and customization. Together, they form a comprehensive data strategy toolkit that bridges reporting with action.