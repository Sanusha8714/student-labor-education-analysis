# STUDENTS LABOR EDUCATION ANALYSIS
This project analyzes a dataset of 4,000 students that combines traditional academic indicators (GPA, attendance) with modern "edge learning" indicators — labor/practical activity, AI and IoT device engagement, digital platform usage, and behavioral/soft-skill scores. The goal is to understand how a student's academic performance relates to their practical involvement, technology engagement, and overall behavior, and to use these patterns to support better monitoring and intervention strategies in an academic institution.
## OBJECTIVES
Understand a dataset blending academic, labor, and technology-engagement data.
Clean and validate the data (types, missing values, duplicates).
Explore patterns via univariate and bivariate analysis.
Examine how GPA relates to attendance, labor activity, AI engagement, gender, and department.
Summarize findings into insights, recommendations, and suggestions.
## DIFFERENT PHASES
   1. Data Collection
   2. Data Transformation & EDA
   3. Analysis Report
## DATA COLLECTION
Datasets were searched for on Kaggle, Google Dataset Search, and other open data repositories, looking for one combining academic performance, labor engagement, and technology usage. Candidates were evaluated on row count, column count, missing values, duplicates, and relevance to the project's focus. Since few datasets matched this exact combination, the Edge Labor Education Dataset (4,000 rows, 30 columns) was downloaded and confirmed to have no missing values or duplicates.
## DATA TRANSFORMATION & EXPLORATION
##### The main purpose of EDA is to understand:
- Distribution of variables
- Frequency of categories
- Average values
- Minimum and maximum values
- Variation in data
- Relationships between variables
- Possible outliers
- Important patterns and trends
### Cleaning method:
The dataset was inspected using structure and summary checks (`info()`, `dtypes`, `describe()`, `isnull().sum()`, `duplicated().sum()`) to verify data types, statistics, missing values, and duplicate rows.
### Main things checked:
Column data types, value ranges/statistics of numeric fields, presence of nulls, and presence of duplicate records.
### Main exploration focus:
Distribution of individual variables (age, department, gender, GPA, attendance, performance category, engagement level, monitoring status) and relationships between key variable pairs (attendance vs. GPA, AI engagement vs. practical skill, labor activity vs. task completion, gender/department vs. performance), along with an overall correlation check among numeric features.
### Changes made:
No missing values or duplicates were found, so no imputation, row removal, or transformation was required — the dataset was already clean and analysis-ready.
## TOOLS & TECHNOLOGIES
-Python 
-pandas 
-numpy 
-matplotlib
-seaborn 
-Jupyter Notebook
## ANALYSIS REPORT
#### Analysis:
The analysis will consist of:
- summary statistics
- univariate analysis
- bivariate analysis
- histograms
- boxplots
- count plots
- scatter plots
correlation heatmap
#### Conclusion:
- Demographics are fairly uniform; performance and engagement levels vary.
- Attendance and gender don't strongly determine GPA.
- AI/tech engagement positively links to practical skill development.
- Weak overall correlation suggests many small factors drive outcomes, not one dominant driver.
#### Recommendations:
- Encourage more AI/digital tool use to boost practical skills.
- Evaluate deeper engagement metrics, not just attendance, when assessing progress.
- Streamline monitoring to cut down "delayed" status cases.
- Review low-performing departments individually rather than uniformly.
#### Suggestions"
- Move toward real-time monitoring and faster follow-ups.
- Flag low-engagement students earlier using Personalized Intervention data.
- Apply multivariate/predictive modeling for deeper insight.
- Track AI/IoT engagement trends over time.
