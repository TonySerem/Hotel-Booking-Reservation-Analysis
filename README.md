# Hotel-Booking-Reservation-Analysis
# HR-Attrition-Analysis
We have a hotel dataset containing Resort and City hotel data from 2015-2017, our central interest is to get insight from the  year 2016 under resort hotel during the summer period (July & August). Although we will need to see insight on other months too.
Our other focuses are cancellation level, average daily rate and revenue made compared to revenue lost on a monthly basis.

## Dashboard Preview
## 1. Attrition by Employee Satisfaction, Employee Working Years and Gender
Layout: The dashboard is divided into six main sections: Total Revenue Generated and Total Revenue Loss by Month, Average Daily Rate and % Total Cancellations by Month, Cancellations by Weekdays, Average Daily Rate and Cancellation Rates
<img width="905" height="509" alt="Dashboard Screenshot" src="https://github.com/user-attachments/assets/a5b22c8b-8e7d-4ca7-8cf9-be6edafe05fd" />


## 2. Attrition by Job Role and Employee Education
Description: The dashboard includes the key metrics such as Total number of Employees and Attrition Rate.
Layout: The dashboard is divided into three main sections: Attrition by Job Role, Attrition by Employee Working Years, Attrition by Employees Education.
Key Metrics:
-	Total number of Employees: 2,925
-	Attrition Rate: 17%
<img width="869" height="477" alt="Dashboard 2" src="https://github.com/user-attachments/assets/a5206d6c-7aa0-4d62-8f91-87efaff467c5" />


## 3. Age And Performance Attrition
Description: The dashboard includes the key metrics such as Total number of Employees and Attrition Rate.
Layout: The dashboard is divided into two main sections: Attrition by Age bracket and Gender and Attrition by Employee Performance.
Key Metrics:
-	Total number of Employees: 2,925
-	Attrition Rate: 17%
<img width="881" height="474" alt="Dashboard 3" src="https://github.com/user-attachments/assets/21989eb4-11db-4ebe-b7a5-f21b5e2fc73b" />

  ## Tools Used
- Power Bi
- Power Query
- DAX

## Data Preparation - Power Query
- Removed top rows
- Changed the first row to be headers
- Removed columns 40-49 which had no meaningful information
- Added a conditional column called distance status to group Employee distance to work into: Near by, Far and Very Far
- Added a conditional column called Employee Working Years to group Employee Working Years into: between 0-10, 11-20 and 21-30
- Added a conditional column called Employee Satisfaction to group Employee Satisfaction into: Very Satissfied, Satissfied and Dissatisfied
- Added a conditional column called Age Group to group Employee's Age into: 18-25, 26-35, 36-45, 46-55 and 56 plus

## DAX Measures
- Total Employees
- Total Attrition
- Inactive Employees
- Low Performance Employees
- High Performance Employees
- Department Attrition
  
## Objectives
- The primary purpose of this HR attrition analysis is to identify the factors driving employee departures, predict attrition trends, and implement evidence-based strategies that improve employee retention, reduce costs, and strengthen overall organizational performance

## Analysis
- Key performance indicators (KPI's); Total Number of Employees and Attrition Rate
- Attrition by Employee's Working Years
- Attrition by Employee Satisfaction
- Attrition by Distance to Work
- Attriton by Department
- Attrition BY Gender
- Attrition by Job Role
- Attrition by Employee Working Years
- Attrition by Employees Education

## Filters
- Gender
  
## Key Findings and Insights
- Total Number of Employees: 2,925
- Attrition Rate: 17%
- Attrition by Employee's Working Years:
  Employees with 0–10 years of total working experience had the highest attrition (378), while employees with 31 or more years of working experience had the lowest attrition (11).
- Attrition by Employee Satisfaction:
  Dissatisfied employees had the highest attrition (151), followed by Very Satisfied employees (134), Very Dissatisfied employees (111), and Satisfied employees (96).
- Attrition by Distance to Work:
  Dissatisfied employees had the highest attrition (151), followed by Very Satisfied employees (134), Very Dissatisfied employees (111), and Satisfied employees (96).
- Attrition by Department:
  The Research & Development (R&D) department recorded the highest attrition (282), followed by Sales (186) and Human Resources (HR) (24)
- Attrition by Gender:
  Male employees accounted for 63% of total attrition, while female employees accounted for 37%
- Attrition by Job Role:
 Among the job roles, Laboratory Technician had the highest attrition (130), while Research Director had the lowest attrition (5).
- Attrition by Employee's Education:
 Employees with a Bachelor's degree had the highest attrition (204), while employees with an Associate degree had the lowest attrition (93).
- Attrition by Age Bucket:
  Employees between the age of 26-35 years had the highest attrition (242), while Employees with the age of 36 plus years had the lowest attrition (17).
  
## Conclusion
The HR attrition analysis revealed that the organization has an overall attrition rate of 17%, with employee turnover being concentrated within specific groups rather than evenly distributed across the workforce. Employees with 0–10 years of working experience, those aged 26–35 years, and employees in the Research & Development (R&D) department experienced the highest levels of attrition. Additionally, Laboratory Technicians, employees holding a Bachelor's degree, and male employees accounted for a significant proportion of employee departures.

The analysis also indicates that employee satisfaction is an important factor influencing retention, with dissatisfied employees recording the highest attrition. However, the relatively high turnover among very satisfied employees suggests that factors beyond satisfaction—such as career growth opportunities, compensation, workload, or external job opportunities—may also contribute to employees leaving the organization.

 ## Recommendations
To improve retention, the organization should prioritize retention strategies for high-risk employee groups by strengthening career development programs, reviewing compensation and benefits, enhancing employee engagement, and conducting targeted stay and exit interviews. Focusing on these areas will help reduce employee turnover, retain valuable talent, lower recruitment and training costs, and improve overall organizational performance.
