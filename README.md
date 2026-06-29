# Hotel-Booking-Reservation-Analysis
# HR-Attrition-Analysis
We have a hotel dataset containing Resort and City hotel data from 2015-2017, our central interest is to get insight from the  year 2016 under resort hotel during the summer period (July & August). Although we will need to see insight on other months too.
Our other focuses are cancellation level, average daily rate and revenue made compared to revenue lost on a monthly basis.

## Dashboard Preview
Layout: The dashboard is divided into six main sections: Total Revenue Generated and Total Revenue Loss by Month, Average Daily Rate and % Total Cancellations by Month, Cancellations by Weekdays, Average Daily Rate, Cancellation Rates and Key Recommendations.

<img width="905" height="509" alt="Dashboard Screenshot" src="https://github.com/user-attachments/assets/a5b22c8b-8e7d-4ca7-8cf9-be6edafe05fd" />

  ## Tools Used
- Power Bi
- Power Query
- DAX

## Data Preparation - Power Query
- Promoted the first row to be headers
- Added a conditional column called Lead Time Transformed to group the Lead time to 0-30 days and >30 days
- Removed a column named column 18 which only had nulls
- Created a Table called Lookup Table from the original table which has two columns: Hotel Type and their Indexes.

## DAX Measures
- Created a Calendar Table
- Number of Transactions
- % Total Cancellations
- Average Daily Rate
- Total Cancellations
- Total Revenue
- Total Revenue Loss
  
## Objectives
- Our purpose for this analysis is to know the following: Cancellation Level, Average Daily Rate and Revenue made compared to Revenue lost on a monthly basis.
  
## Analysis
-  Total Revenue Generated and Total Revenue Loss by Month
-  Average Daily Rate and % Total Cancellations by Month
-  Cancellations by Weekdays
-  Average Daily Rate by days
-  Cancellations Rates by days

## Key Findings and Insights
- There is a gradual increase in both Total Revenue made and Total Revenue lost from January to August followed by by gradual decrease from August to December.
- August has the highest Total Revenue ($1,844,836), followed by July ($1,590,291)
- August has the highest Total Revenue Lost ($1,052,699), followed by July ($717,602)
- The Average Daily Rate is highest in August ($142.9), followed by July ($125.5) and lowest in January ($64.8)
- Cancellations by Weekdays is as follows from highest to lowest: Thursday (596), Saturday (543), Monday (542), Friday (498), Wednesday (482), Sunday (336), Tuesday (327)
- The Average Daily Rate between 0-30 days is $155.1 while the Average Daily Rate when days > 30 is $128.4
- The Cancellations between 0-30 days is 39.08% while the Cancellations days > 30 is 19.17%
  
## Conclusion
The HR attrition analysis revealed that the organization has an overall attrition rate of 17%, with employee turnover being concentrated within specific groups rather than evenly distributed across the workforce. Employees with 0–10 years of working experience, those aged 26–35 years, and employees in the Research & Development (R&D) department experienced the highest levels of attrition. Additionally, Laboratory Technicians, employees holding a Bachelor's degree, and male employees accounted for a significant proportion of employee departures.

The analysis also indicates that employee satisfaction is an important factor influencing retention, with dissatisfied employees recording the highest attrition. However, the relatively high turnover among very satisfied employees suggests that factors beyond satisfaction—such as career growth opportunities, compensation, workload, or external job opportunities—may also contribute to employees leaving the organization.

 ## Recommendations
To improve retention, the organization should prioritize retention strategies for high-risk employee groups by strengthening career development programs, reviewing compensation and benefits, enhancing employee engagement, and conducting targeted stay and exit interviews. Focusing on these areas will help reduce employee turnover, retain valuable talent, lower recruitment and training costs, and improve overall organizational performance.
