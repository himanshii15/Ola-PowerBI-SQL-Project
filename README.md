# Ola-Ride-Analytics
**Tools used : Excel,MS SQL Server,Power BI**

[Dataset used](https://docs.google.com/spreadsheets/d/1tfhGked6AI4C1TwjwBMm2nvJPln1pw93/edit?usp=sharing&ouid=104819260278317021909&rtpof=true&sd=true)

[SQL Analysis-code](https://github.com/himanshii15/Ola-PowerBI-SQL-Project/blob/16ddd0c739801ea428faddf60d9647d023e4ac58/sql_analysis)

[Power BI Dashboard- click to view](https://github.com/himanshii15/Ola-PowerBI-SQL-Project/blob/16ddd0c739801ea428faddf60d9647d023e4ac58/olaproject.pdf)

[Power BI Dashboard- click to interact](https://github.com/himanshii15/Ola-PowerBI-SQL-Project/blob/16ddd0c739801ea428faddf60d9647d023e4ac58/olaproject.pbix)


# Business Problem
OLA faced challenges in understanding ride trends, cancellation reasons, customer satisfaction, and revenue fluctuations. Lack of centralized, visual insights made it difficult for decision-makers to identify key performance drivers and areas for improvement.


# Solution Plan
- To help OLA gain valuable insights from their April 2024 ride booking data, I will utilize SQL and data visualization with Power BI to extract meaningful information and perform in-depth analysis. The process will include data cleaning, transformation, and exploration.

- By leveraging SQL’s capabilities, I aim to uncover key performance metrics such as total successful rides, cancellation breakdowns, average ratings, ride distribution by vehicle type, and revenue trends. These insights will help identify service gaps and customer behavior patterns.
  
- Once the data is prepared, I will use Power BI to present the findings through interactive and visually engaging dashboards. These visuals will empower OLA’s stakeholders to understand booking trends, cancellation reasons, top-performing customers, and vehicle performance at a glance.

- I plan to design a dynamic Power BI dashboard that allows users to explore KPIs like booking status, customer/driver ratings, revenue contribution, and incomplete ride reasons. The goal is to deliver actionable insights that support data-driven decision-making and help optimize OLA’s operational efficiency and customer experience.


# Execution

**1) Find the average ride distance for each vehicle type**

 ![image](https://github.com/user-attachments/assets/356a283b-d912-4ca6-b746-e251b2c386d7)

 ![image](https://github.com/user-attachments/assets/685f497a-95d1-4817-832d-0bddeca9985c)

Understanding the average ride distance for each vehicle type helps optimize vehicle allocation and pricing strategies. For instance, longer average distances for certain types (like Prime) could justify premium pricing or targeted promotions.

**2) Get the total number of cancelled rides by customers**

![image](https://github.com/user-attachments/assets/35d05811-ac27-4a69-b6e4-41b87e3008bf)

![image](https://github.com/user-attachments/assets/5abe6ffc-1f6b-4ea9-b9ba-732c7a8f5dd0)

A high number of customer cancellations can indicate dissatisfaction, delays, or app usability issues. Tracking this metric helps the company reduce cancellations through improved UX, communication, or incentives.

**3) List the top 5 customers who booked the highest number of rides**

![image](https://github.com/user-attachments/assets/7ffcb4db-97c6-417a-a772-4bfec824b8ec)

![image](https://github.com/user-attachments/assets/d8bbf8e6-0c47-4e06-9260-c91b8a1d53ee)

Identifying top customers allows the business to implement loyalty rewards, targeted marketing, and personalized services to retain high-value users and encourage repeat usage.

**4) Get the number of rides cancelled by drivers due to personal and car-related issues**

![image](https://github.com/user-attachments/assets/58812478-8435-414e-863c-39c7fd46d52f)

![image](https://github.com/user-attachments/assets/34f2fc9e-d956-49b4-915b-b8d7591e58cd)

Cancellations due to driver-side issues highlight operational inefficiencies or maintenance problems. Reducing these can improve service reliability and customer trust.

**5) Find the maximum and minimum driver ratings for Prime Sedan bookings**

![image](https://github.com/user-attachments/assets/f3367e6d-6cf9-400d-bf35-af2df89517c1)

![image](https://github.com/user-attachments/assets/b16b6fc7-17f1-42bd-b1a8-e7855a313677)

Analyzing the spread of driver ratings for premium vehicles like Prime Sedan helps maintain service quality. Large gaps may indicate inconsistent customer experience needing driver feedback or retraining.

**6) Find the average customer rating per vehicle type**

![image](https://github.com/user-attachments/assets/dea8d390-0243-45f4-b229-79ee0c196dd3)

![image](https://github.com/user-attachments/assets/59c9884d-889f-4d6b-a603-6178c2966d99)

This metric reveals which vehicle categories offer the most satisfying ride experience. Poor ratings in specific types may require improvements in vehicle comfort, cleanliness, or driver behavior.

**7) Calculate the total booking value of rides completed successfully**

![image](https://github.com/user-attachments/assets/68ea2d5d-6b96-4289-9f4c-f0f07a96758b)

![image](https://github.com/user-attachments/assets/6b99fff2-ea77-4eeb-a32f-e38dc2cf8a9a)

This helps measure total revenue generated from completed rides, a critical KPI for financial analysis, revenue forecasting, and performance benchmarking.

**8) How many incomplete rides occurred for each reason?**

![image](https://github.com/user-attachments/assets/9c4921b0-5306-40cc-af1b-278abf75947e)

![image](https://github.com/user-attachments/assets/b9413274-13c5-4f96-8d81-48198b018134)

Knowing why rides were incomplete helps pinpoint service failures—whether technical, logistical, or customer-related—enabling focused corrective actions to minimize disruptions.

















