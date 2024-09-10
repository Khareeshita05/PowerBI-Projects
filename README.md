## Problem Statement

This dashboard provides insights into the experiences and satisfaction of professionals in various data-related job roles. It enables organizations and recruiters to understand how professionals from different job titles, such as Data Analysts, Data Scientists, Data Engineers, Data Architects, and Database Developers, experience challenges and success in their careers. It highlights key factors such as salary satisfaction, work-life balance, favorite programming languages, and the difficulty of breaking into the data field.

The dashboard also provides a breakdown of average salaries by job title and identifies areas where professionals might need more support, especially for those new to the data field. It gives a holistic view of the data community, helping companies make data-driven decisions about hiring, retention, and training.

### Steps Followed

- **Step 1**: Load the data (CSV/Excel file) into Power BI Desktop.
- **Step 2**: Open Power Query Editor and check for "Column Distribution," "Column Quality," and "Column Profile" to ensure there are no errors or missing values.
- **Step 3**: Profile the dataset to ensure that null or irrelevant data is either removed or ignored for calculations like average salary or satisfaction ratings.
- **Step 4**: Perform data transformation to prepare calculated columns for grouping professionals based on job titles (e.g., Data Analyst, Data Scientist).
- **Step 5**: In the report view, apply theme colors and formatting for better visualization.
  
### Dashboard Components

- **Total Number of Surveyees**: A **Card visual** is used to display the total number of participants in the survey.
  
- **Average Age of Surveyees**: Another **Card visual** shows the average age of all respondents, providing insight into the age demographics of professionals in the data field.

- **Average Salary by Job Title**: A **Stacked Bar Chart** compares the average salary across different job titles such as Data Analyst, Data Scientist, Data Engineer, etc. This visualization helps to see salary distribution by role.

- **Difficulty in Breaking into Data**: A **Pie Chart** displays the percentage of respondents who faced different levels of difficulty when first entering the data profession. This metric is crucial for understanding the challenges newcomers face in different job roles.

- **Favorite Programming Language**: A **Column Chart** shows the most popular programming languages (e.g., Python, R, Java, JavaScript, C/C++) among different job titles. This helps to understand which languages are preferred by Data Analysts, Scientists, Engineers, etc.

- **Average Salary (Donut Chart)**: A **Donut Chart** visualizes the overall average salary of all respondents, highlighting salary trends across the data industry.

- **Satisfaction with Salary**: A **Gauge visual** measures how satisfied professionals are with their current salary. The gauge shows how close the satisfaction level is to a desired threshold.

- **Satisfaction with Work-Life Balance**: Another **Gauge visual** measures satisfaction with work-life balance, providing insight into whether professionals are content with their working conditions.

### Additional Insights

- **Job Titles & Favorite Languages**: Data professionals have preferences for programming languages based on their roles. For example:
  - Python is the most preffered Language AMONG professionals
  - Data Engineers could favor languages like Python and R
  - The chart breaks down these preferences, helping organizations understand skill demands.

- **Difficulty Levels**: Each job role experiences different levels of difficulty when first breaking into data. Some roles might have steeper learning curves, requiring more onboarding or training, and this is reflected in the pie chart.
