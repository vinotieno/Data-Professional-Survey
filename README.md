# Data-Professional-Survey
## This power bi project focuses in analyzing survey responses from data professionals all over the world.
### Table of contents
- Project Overview
- Data Sources
- Tools
- Data cleaning and preparation
- Exploratory Data Analysis
- Data Visualization
- Results/Findings
- Recommendation
- Technical Implementation
- References

### Project Overview
- This project analyzes survey responses from data professionals to uncover trends in salary distribution, job satisfaction, career transitions,demographics(Gender, Ethnicity) etc. 
- The goal of this project is to:
  - Help organizations and educational institutions develop policies and curricula that align with industry needs.
  - Understand current trends in the data profession, including skills in demand, tools used, and industry shifts.
  - Evaluate the skills and competencies of data professionals to identify gaps and areas for improvement.
  - Analyze compensation data to provide insights into salary ranges based on location, and job roles.
  - Assess the level of job satisfaction among data professionals and identify factors that contribute to it.
  - Identify training and development needs based on the skills reported by professionals.
 
 
- This analysis is performed using Power BI, with data exploration, visualization, and insights derived from various survey questions.

### Data Sources
- The Primary dataset used for this analysis is the "Data Professional Survey.xlsx" file containing the survey response from data professional all over the world.
- The dataset contained these columns:
Unique ID,	Email,	Date Taken (America/New_York), Q1 - Which Title Best Fits your Current Role?.1, Q2 - Did you switch careers into Data?,
Q3 - Current Yearly Salary (in USD), Average salary,	Q4 - What Industry do you work in?.1,
Q5 - Favorite Programming Language.1, Q6 - How Happy are you in your Current Position with the following? (Salary),
Q6 - How Happy are you in your Current Position with the following? (Work/Life Balance),	Q6 - How Happy are you in your Current Position with the following? (Coworkers),	Q6 - How Happy are you in your Current Position with the following? (Management),	Q6 - How Happy are you in your Current Position with the following? (Upward Mobility),	Q6 - How Happy are you in your Current Position with the following? (Learning New Things),	Q7 - How difficult was it for you to break into Data?,	Q8 - If you were to look for a new job today, what would be the most important t,	Q9 - Male/Female?,	Q10 - Current Age,	Q11 - Which Country do you live in?.1,	Q12 - Highest Level of Education,	Q13 - Ethnicity.1,	Q3 - Current Yearly Salary (in USD) - Copy.1,	Q3 - Current Yearly Salary (in USD) - Copy.2

### Tools
- The following tools were used:
    - Excel- Source of data [Download here][Data Professional Survey.xlsx](https://github.com/user-attachments/files/18940838/Data.Professional.Survey.xlsx)

    - Power Query- Data Cleaning
    - Power BI- Creating Reports
    
### Data Cleaning and Preparatiion
- During the data cleaning processes in power query, the following steps were considered:
   - Data Loading and inspectation.
   - Handling Missing Values- using the find and replace.
   - Standardizing formats (dates, text, numbers).
   - Deleting Empty Columns
   - Using Delimiter to split columns
   - Creation of a duplicate column in cleaning the SALARY column, Separeted the digits to non-digit, using the find and replace,Added another column to get the average 
     salary. 

### Exploratory Data Analysis
 - The Key Aspects for this project is:
    - Whats your favorite programming language based on your level of education?
    - Whats the average salary of data professional based on job title?
    - How difficult was it for you to break into Data?
    - Whats the average number of people who are happy with there current salary?
    - Whats the average number of people who are happy with work/life balance?
    - Which Country do you live in?

  
  ### Data Visualization

[Data Professional Survey Takers.pdf](https://github.com/user-attachments/files/18943018/Data.Professional.Survey.Takers.pdf)







![Chart5](https://github.com/user-attachments/assets/76bf8c04-5668-40ba-bffb-5c7e66cadfd3)





### Results and Findings
- The total number of data professional individual who participated in this survey is 630.
- The Avereage Age of these survey takers was 29 year old.
- Based on the results,majority of students pursuing a Bachelor's degree prefer learning Python over other programming languages.
- So many people are not happy with there current salary. This is evident in the analysis where the majority are in the average of 4.27 (In a scale of 1-10)
- The probability of people who are happy and not happy with there work/life balance is equal.
- Based on the results,data scientist are the highest paid data professionals with an average salary of 94 usd.
  

### Recommendation
- Based on the analysis, I would recommed the following actions:
    - Encourage continuous learning and upskilling programs.
    - Focus on career growth opportunities to improve employee retention.
    - Encourage organizations to offer structured internships & apprenticeships for new graduates,Provide on-the-job training for career switchers so that they dont find 
      difficulties breaking into the new fields.
    - Encourage organizations to Partner with universities, coding bootcamps, and scholarship programs to create entry pathways.

### Technical Implementation
- Power query commands
- Power BI Charts

### References
1. Data Analysis with Excel by Kenji Explains
2. Data Analysis With Excel By Pavan Lalwani  










  
   



