# HR Attrition Analysis Dashboard (MySQL + Power BI)

### Project Overview

This project explores employee attrition patterns in a fictional organization. I used **MySQL** to prepare and analyze the data, then built an interactive **Power BI dashboard** to present insights that can support HR decision-making.

### Data Sources
The primary data set used for this analysis is fictional and was created by IBM scientists. [Download Here](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)


### Tools Used
- **MySQL** – For filtering and exploratory data analysis.
- **Power BI** – For data visualization and dashboard design


## Project Workflow

### 1. Data Analysis (MySQL)
- Explored raw HR data covering job role, tenure, age, gender, education, satisfaction, and attrition status.
- Created calculated columns and grouped data:
  - **Tenure bands** (e.g., under 5 years, 5–10 years)
  - **Age groups**
  - **Attrition counts and rates** by key categories
- Exported summary tables for clean import into Power BI

### 2. Dashboard Development (Power BI)
- Created cards for Key Insights and Total employees, and built visuals like:
  - Attrition by Tenure Group
  - Attrition by Job Role
  - Attrition by Age Group and Gender

  
> Some variables like **Job Satisfaction** were explored but excluded from visuals due to minimal variation across roles.

## Key Insights for HR

- **Early attrition is high**: Employees with under 5 years’ tenure accounted for the majority of attrition (24.3%), signaling onboarding or early-career engagement issues.
- **Younger and single employees leave more**: Highest attrition occurred among employees aged **18–24**, especially those who were **single**.
- **Overtime is a strong risk factor**: 53.6% of employees who left were working overtime, compared to 46.4% who didn’t.
- **Work-life balance matters**: Employees who rated their work-life balance as **“Poor”** had more than double the attrition rate compared to those rating it as “Good” or “Excellent”.
- **Certain job roles are more vulnerable**: High turnover was observed in roles like **Laboratory Technician** and **Sales Executive**, which may require role-specific retention strategies.




