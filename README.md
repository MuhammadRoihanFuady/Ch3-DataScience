# Ch3-DataScience
I have completed a series of tasks related to data analysis and machine learning. Here's a detailed explanation of what I've done:

1. **Descriptive Statistics for Salary by Marital Status and Gender:**
   I used Pandas to group the data by "MaritalDesc" and "Sex" columns to calculate statistics such as minimum, median, maximum, and average salary. The results were stored in a new dataframe.

2. **Top-5 Reasons for Termination:**
   I calculated the five most common reasons for employee termination from the "TermReason" column and displayed the results in a dataframe.

3. **Most Recruitment by "Exceeds" Performance Score:**
   I calculated the number of employees with an "Exceeds" performance score for each recruitment source and sorted the results. The results were also displayed in a dataframe.

4. **Number of Managers in Each Department:**
   I calculated the number of unique managers in each department and displayed the results in a dataframe.

5. **Termination Ratio by Gender:**
   I calculated the ratio of employee terminations based on gender using the value_counts(normalize=True) function.

6. **Visualization: Termination Ratio by Gender (Bar Plot)**
   I created a bar plot to visualize the termination ratio by gender.

7. **Visualization: Scatter Plot of Salary vs. Engagement Survey:**
   I created a scatter plot to compare the "Salary" column with the "EngagementSurvey" while using different colors to represent termination status ("Termd").

8. **Visualization: Bar Chart of Termination Count by Department:**
   I created a bar chart to visualize the count of employee terminations by department.

9. **Visualization: Pie Chart of Termination by Position:**
   I created a pie chart to show the percentage of employee terminations by position.

10. **Visualization: Box Plot of Salary by Marital Status (MaritalDesc) with Termination Coloring:**
    I used a box plot to visualize salary based on marital status and colored it based on termination status.

11. **Visualization: Pair Plot for Selected Features with Termination Coloring:**
    I used a pair plot to compare selected features with coloring based on termination status.

12. **Creation of "Age" Feature in Years:**
    I calculated employees' ages based on the "DOB" column by subtracting their birth year from 2022.

13. **Min-Max Scaling on the "Salary" Feature:**
    I applied MinMaxScaler to scale the "Salary" feature to a range between 0 and 1.

14. **Conversion of All Object Data Types to Category:**
    I converted all object data types to the category data type.

15. **Label Encoding on "RecruitmentSource":**
    I used Label Encoder to encode the "RecruitmentSource" column into numerical values.

16. **Label Encoding on "PerformanceScore":**
    I used Label Encoder to encode the "PerformanceScore" column into numerical values.

17. **Separation of Dependent and Independent Variables:**
    I separated the data into dependent (target) and independent (feature) variables.

18. **Splitting Data into Train-Test Sets:**
    I divided the data into training and testing sets with an 80:20 ratio.

19. **Machine Learning Modeling:**
    I employed a machine learning model (Logistic Regression) to predict the "Termd" status and evaluated the results using classification scores such as accuracy, precision, and recall.

20. **Insights:**
    - I provided two insights related to the data I analyzed. First, I noted that there may be a relationship between an employee's manager and their performance score, influenced by leadership style and team dynamics. Second, I sought to identify the best recruitment sources to minimize the termination ratio.

These tasks helped me explore and analyze HR data, perform data preprocessing, visualization, and even build a machine learning model to understand the factors affecting employee termination.
