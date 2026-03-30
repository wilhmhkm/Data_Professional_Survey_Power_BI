# 📊 Data Professional Survey Dashboard (Power BI)

![Image Alt](https://github.com/wilhmhkm/Data_Professional_Survey/blob/1fff17f68efd9ce3f683bb7d661f3361b31b7ae4/Screenshot%202026-03-30%20221759.jpg)

## 📌 Executive Summary
This project presents an interactive **Power BI dashboard** built using real-world survey data collected from ~630 data professionals. The objective was to transform raw, unstructured survey responses into meaningful insights about roles, salaries, skills, and career experiences within the data industry.

Using Power BI’s data transformation and visualization capabilities, the dataset was cleaned, standardized, and modeled to create a user-friendly dashboard. The final output enables quick, high-level insights as well as deeper exploration through interactive visuals.

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

### 1. Data Import
- Imported raw CSV survey data into Power BI  
- Loaded dataset into **Power Query Editor** for transformation  

### 2. Data Cleaning & Transformation
- Removed irrelevant columns (e.g., email, browser metadata)  
- Standardized categorical fields:
  - Simplified job titles (grouped “Other” responses)
  - Cleaned programming languages using delimiter splits  
- Handled inconsistent text inputs using delimiters (e.g., “(”, “:”)  
- Transformed salary ranges:
  - Split into min/max values  
  - Converted to numeric format  
  - Created **average salary column**  
- Fixed data types (text → numeric where needed)  
- Reduced high-cardinality fields by grouping rare values  

### 3. Feature Engineering
- Created:
  - **Average Salary (calculated column)**
  - Aggregated KPIs (average age, total respondents)

### 4. Data Modeling
- Built a single-table model (no joins required)  
- Ensured proper field categorization for visuals  

### 5. Dashboard Development
- Designed interactive dashboard with:
  - KPI cards
  - Comparative charts
  - Country-based filtering  

### 6. UI & Theme Customization
- Applied Power BI themes  
- Improved layout, spacing, and readability  
- Organized visuals for storytelling  

---

## 📊 Key Insights

### 👥 Demographics
- ~630 survey participants  
- Average age: ~30 years  

### 💼 Salary Trends
- Data Scientists earn the highest average salaries  
- Data Analysts are the most represented group  
- Salary varies significantly by country  

### 🌍 Geographic Impact
- Higher salaries observed in the United States  
- Lower averages in other regions reflect cost of living differences  

### 💻 Programming Languages
- Python is the most popular language  
- Other common languages:
  - R  
  - C++  
  - JavaScript  
  - Java  

### 😊 Job Satisfaction
- Work-life balance: moderate (~5.7/10)  
- Salary satisfaction: relatively low  

### 🚪 Entry Difficulty
- Majority reported difficulty entering the data field  
- Some experienced easier transitions  

### ⚖️ Gender Comparison
- Salaries between genders are relatively close  
- Slight variation observed but not significant  

---

## 💡 Recommendations

### 1. Improve Data Collection
- Use structured inputs (dropdowns instead of free text)  
- Reduce inconsistent entries  

### 2. Enhance Data Cleaning
- Standardize:
  - Job titles  
  - Programming languages  
  - Country names  
- Consider preprocessing with SQL or Python  

### 3. Refine Salary Data
- Collect exact salary values instead of ranges  
- Use sliders or numeric inputs in surveys  

### 4. Expand Analysis
- Segment by:
  - Experience level  
  - Industry  
  - Education  
- Perform deeper statistical analysis  

### 5. Improve Dashboard UX
- Add slicers (filters) for better interactivity  
- Include drill-through pages  
- Optimize layout for storytelling  

### 6. Future Enhancements
- Connect to live datasets  
- Add predictive analytics  
- Incorporate time-series analysis
