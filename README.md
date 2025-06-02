📊 Job Postings Data Analysis 2025

🔍 Overview
This Power BI dashboard provides a comprehensive analysis of job postings in the data analytics field for the year 2025. It enables users to explore job trends by role, experience level, skill demand, industry, salary range, and geography.

![Image](https://github.com/user-attachments/assets/b93a8380-b968-413b-8b27-150342931fb1)


🧩 Key Components

1. Header
Title: Job Postings Data Analysis 2025

Clearly defines the report's purpose and time scope.

2. KPIs (Top Row)
- Total Job Postings (15.00K): Total number of data job listings analyzed.

- Average Overall Salary (115.35K): The mean salary across all postings.

3. Job Postings by Experience Category
- Visual: Line chart

- Categories: Level_1 to Level_4 (custom groupings based on experience such as Entry, Mid, Senior, Executive).

- Insight: Distribution shows a slight decline in postings with increasing seniority.

4. Top 5 Industries and No of Job Postings
- Visual: Bar chart

- Industries: Automotive, Consulting, Media, Retail, Technology.

- Insight: Automotive and Media lead in demand for data roles.

5. No of Data Analyst Postings by Skills
- Visual: Bar chart

- Skills Included: Python, SQL, Tableau, R Prog, Others.

- Insight: "Others" and "Python" dominate skill requirements for Data Analysts.

6. Job Postings for Data Analyst by Country
- Visual: Map

- Locations: Includes US, UK, Israel, France, Netherlands, Austria, etc.

- Insight: Geospatial distribution of Data Analyst roles across continents.

7. Average Salary by Countries
- Visual: Horizontal bar chart

- Countries: Switzerland, Denmark, Norway, US, UK.

- Insight: Switzerland offers the highest average salary among the listed countries.

8. Filters
- Job Title Dropdown: Allows filtering by specific job titles.

- Date Posted Slider: Filters job postings between Jan 1, 2024, and Apr 30, 2025.

🛠 Data Source: Dataset from Kaggle.

Data Cleaning: Performed in Power Query Editor (e.g., custom skill categorization using Text.Contains()).

Measures & Calculations: Implemented in DAX for totals, averages, and conditional logic.

📌 Use Cases
- Job market research for data roles.

- Salary benchmarking across countries.

- Skill demand trend analysis.

- Strategic hiring and HR planning.

- Career guidance for aspiring data professionals.

📋 Notes

- Experience categories (Level_1, Level_2, etc.) are custom-defined.

- Skill categorization handles multi-skill strings via Text.Contains().

- The dashboard focuses on Data Analyst roles but could be extended to others.
