# Student-performance-Analysis

## Project Overview 

This data analysis project aims to provide insights into the students performance of a private learning provider. By analyzing various aspects of the students data, we seek to identify trends , make data-driven recommendations and gain a deeper understanding of the students' performance.

### Data Source
The primary data set used for this analysis is the "Students_Grading_Dataset.csv" file. It consists of 5,000 real records collected from a private learning provider. It includes key attributes to explore patterns, correlations, and insights related to academic performance, student behavior, and various demographic factors. Variables include: gender, department, parental education, grades, etc.

### Tools 

Python (Data Analysis)
- Pandas - Data cleaning
- Matplotlib and seaborn - Visualization

### Data cleaning / Preparation
In the initial data preparation phase , the following tasks were performed :
Importing necessary libraries
Data loading and Inspection 
Handling missing values and duplicates 
Data cleaning and formatting 

### Exploratory Data Analysis (EDA)
EDA involved exploring the students data to answer key questions such as :
- What is the overall students' perfomance?
- Which factors influence students performance?
- Are there any patterns or trends that differentiate grade categories?
- Which departments have the highest performing students?

Types of EDA used : Univariate , Bivariate and Multivariate Analysis

### EDA findings 
1. Majority of the students (30%) had a high perfomance and achieved Grade A.
2. There's a positive correlation between parent education level and student grades. As the parent's education level increases, the frequency of students receiving higher grades (A) also  increases.
3. There are gender imbalances where Male gender dominates most of the departments
4. However, there's a balanced distribution in the business department indicating gender parity suggesting this field is more appealing to both genders.
5. Students who got an F show equal or more study hours compared to other grades,which means more study hours donot necessarily lead to higher grades
6. Students with grades C, D, and F tend to show slightly higher median stress levels than those with A or B.

### Recommendations
Based on the analysis, the following actions are recommended: 
- Consider initiatives to encourage more balanced participation (e.g, outreach programs, scholarships, or mentorship opportunities) for the female gender.
- Encourage low performing students to participate in Extra curricular activities to reduce stress levels
- Encourage parents to be more involved in their childrens' education.

### Next steps
- Feature Engineering to enhance model performance by creating meaningful new features
- Predictive modelling to forecast student performance or identify at-risk students early 
- Segmentation Analysis to identify student subgroups with distinct behaviors/needs
- Build dashboard to translate insights into sights (Tableau)




