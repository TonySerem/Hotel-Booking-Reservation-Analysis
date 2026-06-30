# Hotel-Booking-Reservation-Analysis
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
- The Cancellations between 0-30 days is 39.08% while the Cancellations when days > 30 is 19.17%
  
## Conclusion
The Hotel Booking Reservation Analysis revealed that the highest revenue was generated in August followed by July. Also the Revenue was gradually increasing from January to August then Gradually decreasing to December.
The analysis also shows that the highest Revenue lost was also in August followed by July. 
This shows that bookings are high in August and July and more emphasis should be put into these months for more Revenue to be Generated.

The Average Daily Rate is also highest in August followed by July, this shows that we could replicate the promotions/discounts during this months to other months to see if we could make some improvements. we could also increase prices slightly during these months to make more revenue.

The number of cancellations are also generally high, we should follow up to see what causes this cancellations.

 ## Recommendations
- # Hotel-Booking-Reservation-Analysis
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
- The Cancellations between 0-30 days is 39.08% while the Cancellations when days > 30 is 19.17%
  
## Conclusion
The Hotel Booking Reservation Analysis revealed that the highest revenue was generated in August followed by July. Also the Revenue was gradually increasing from January to August then Gradually decreasing to December.
The analysis also shows that the highest Revenue lost was also in August followed by July. 
This shows that bookings are high in August and July and more emphasis should be put into these months for more Revenue to be Generated.

The Average Daily Rate is also highest in August followed by July, this shows that we could replicate the promotions/discounts during this months to other months to see if we could make some improvements. we could also increase prices slightly during these months to make more revenue.

The number of cancellations are also generally high, we should follow up to see what causes this cancellations.

 ## Recommendations
- Consider a carefully managed overbooking strategy during peak months, supported by historical cancellation rates, to maximize occupancy while minimizing customer disruption
- Focus more on booking between 0-30 days during the summer period (July & August)
- Reducung the Average Daily Rate might reduce cancellations


