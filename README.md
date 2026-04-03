# 📊 Data Professional Survey

![Image Alt](https://github.com/wilhmhkm/Data_Professional_Survey/blob/7e6d41936bbd50bf983b3ecafc23487bf8416bcd/Project%20Dashboard.jpg)

**Note on Accessibility:** Because Microsoft Power BI requires a **Work or School (Organizational) account** to publish live URLs, this project is hosted as a local `.pbix` file. [Download the .pbix file here.](./)

## 📌 Executive Summary

In this project, I present an interactive **Power BI dashboard** built using real-world survey data collected from 630 data professionals. My goal is to transform raw, unstructured survey responses into meaningful insights around roles, salaries, skills, and overall career experiences within the data industry.  

I use Power BI’s data transformation and visualization capabilities to clean, standardize, and model the dataset, making it intuitive and analysis-ready. The final dashboard allows users to quickly understand high-level trends while also exploring deeper insights through interactive visuals.

---

## 🛠️ Tools & Technologies
- **Power BI**
  - Power Query (ETL & data cleaning)
  - DAX (basic calculations)
  - Data Modeling & Visualization
- **CSV Dataset** (Survey data from data professionals)
- **Data Visualization Techniques**
  - Bar Charts
  - Column Charts
  - Treemaps
  - Cards
  - Gauges
  - Donut Charts

---

## 🚀 Data Processing Steps

I start by importing the raw CSV survey data into Power BI and loading it into the Power Query Editor for transformation.  

I remove irrelevant columns such as email and browser metadata, then standardize categorical fields by simplifying job titles and grouping “Other” responses. I also clean programming language data using delimiter-based splits and handle inconsistent text inputs using characters like “(” and “:”.  

For salary data, I split ranges into minimum and maximum values, convert them into numeric format, and create an average salary column. I also correct data types where needed and reduce high-cardinality fields by grouping less frequent values.  

I create calculated fields such as average salary and aggregate key metrics like average age and total respondents to support analysis.  

I build a single-table model, ensuring all fields are properly categorized and optimized for visualization.  

I design an interactive dashboard that includes KPI cards, comparative charts, and country-based filtering to support different analytical perspectives.  

To improve usability, I apply Power BI themes, refine layout and spacing, and organize visuals in a way that supports clear and effective storytelling.

---

## 📊 Key Insights

From the dataset, I observe that there are around 630 survey participants with an average age of approximately 30 years.  

I find that Data Scientists earn the highest average salaries, while Data Analysts make up the largest portion of respondents. Salary levels also vary significantly across countries.  

Higher salary levels are observed in the United States, while lower averages in other regions reflect differences in cost of living.  

Python emerges as the most widely used programming language, followed by others such as R, C++, JavaScript, and Java.  

Work-life balance is rated moderately at around 5.7 out of 10, while salary satisfaction appears relatively low among respondents.  

Most respondents report that entering the data field is challenging, although some indicate smoother transitions.  

Salary differences between genders are relatively small, with only slight variations that are not highly significant.  

---

## 💡 Recommendations

I recommend using more structured inputs, such as dropdown menus instead of free text, to reduce inconsistencies in survey responses.  

I focus on standardizing key fields like job titles, programming languages, and country names, and consider preprocessing the data further using SQL or Python for better scalability.  

I suggest collecting exact salary values instead of ranges and using numeric inputs or sliders in surveys to improve accuracy.  

I see opportunities to segment the data further by experience level, industry, and education, and to apply deeper statistical analysis for more insights.  

I enhance interactivity by adding slicers and drill-through pages, and optimize the layout to improve storytelling and usability.  

Looking ahead, I would connect the dashboard to live datasets, incorporate predictive analytics, and introduce time-series analysis to make the solution more dynamic and forward-looking.
