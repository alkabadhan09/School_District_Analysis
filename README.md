# School District Analysis
## Overview
### Background
In the module, we help Maria, a Chief Data Scientist for a City School system, analyze data based on student funding and student standardized test scores. We were tasked to aggregate the data and showcase trends in school performance. The analysis would help the school board in making decisions on budget allotments for city schools. We were able to analyze the data and deliver results in the form of top 5 and bottom 5 performing schools based on the overall passing rate, the average math score received by students in each grade level at each school, the average reading score received by students in each grade level at each school, school performance based on the budget per student, school performance based on the school size, and school performance based on the type of school. 
### Purpose
Maria was notified that the dataset consisting student information appears to have been altered, especially the math and reading scores of Thomas High School 9th graders. We were asked to replace the math and reading scores of Thomas High Schools students with NaNs while keeping the rest of the data as is. We also had to repeat the analysis that we had preiously done with the new changes in order to help the school board make the best decisions for the schools.  
## Results

* **How is the district summary affected?**

District Summary-Before: 
![District_Sum_Before](https://user-images.githubusercontent.com/107225715/178079491-8d7848ca-4d08-4aa4-9c57-8f542e30ee7f.png)
    
District Summary - After:
![District_Sum_After](https://user-images.githubusercontent.com/107225715/178079535-ef10392d-b5ef-4514-9754-5461ff1ed8e9.png)

Replacing the math and reading scores of Thomas High School 9th graders did not have a major impact on the district summary as it only decreased the overall passing percentage by 0.1. It is important to consider that only 461 students' scores were replaced by NaNs and the total student count was 39,170 so the scores can only impact the averages so much.


* **How is the school summary affected?**

School Summary - Before:
![School_Sum_Before](https://user-images.githubusercontent.com/107225715/178081595-f9c7aa32-74de-4ba9-88e8-488ee5d0297d.png)

School Summary - After:
![School_Sum_After](https://user-images.githubusercontent.com/107225715/178081620-4dc4bfed-bee7-49bc-b8dd-6ca03b4b806d.png)

As indicated above by the school summary comparisons above, replacing the scores did not have a major impact on Thomas High School's performance as the overall passing percentage only went down by 0.4 percent. 


* **How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

Top 5 Schools Before and After: 

![TS_Before](https://user-images.githubusercontent.com/107225715/178084030-10cb1771-12ca-4604-89c1-38e8ebb18940.png)
![TS-After](https://user-images.githubusercontent.com/107225715/178084033-afe12a7b-32bb-4154-8d36-c972c970e85a.png)

Bottom 5 Schools Before and After:

![BS_Before](https://user-images.githubusercontent.com/107225715/178084047-e9cfec52-4894-47c7-9e91-ec3bab40d654.png)
![BS_After](https://user-images.githubusercontent.com/107225715/178084050-7b91cfd4-5e2d-45d1-936e-f94eefeab14c.png)


Replacing the scores did not have any impact on the ranking of schools from top to bottom performing schools as indicated above. 


* **Affect on Math and Reading Scores by Grade:**

Math and Reading Scores - Before:

![MS-Before](https://user-images.githubusercontent.com/107225715/178082930-e0f5ffae-6241-4c38-93dc-b4ee2c5fe3b3.png)
![RS-Before](https://user-images.githubusercontent.com/107225715/178082937-4ec7ad6e-8ff3-4d57-b150-d2130a186226.png)

Math and Reading Scores - After: 

![MS-After](https://user-images.githubusercontent.com/107225715/178083021-b0befc9d-bc2c-430f-a990-c171d66d6d88.png)
![RS-After](https://user-images.githubusercontent.com/107225715/178083029-613b9e22-95da-4c76-881d-2a1b4e468567.png)

The only change happened in this category was that reading and math scores of the ninth graders were rplaced by NaNs after the code is updated. 



* **Affect on Scores by School Spending Before and After**

![Spending_Before](https://user-images.githubusercontent.com/107225715/178084533-ce8614dd-f9ce-49a0-9803-321ed20859f2.png)
![Spending_After](https://user-images.githubusercontent.com/107225715/178084534-c89cd74b-b05d-46c7-8d51-7554d7d9cf07.png)

Since Thomas High School falls into the $631-645 spending range, that bracket is affected and has decreased by 0.01 percent in every category and by 0.07% in overall passing category.


* **Affect on Scores by School Size Before and After:**

![Size_Before](https://user-images.githubusercontent.com/107225715/178084538-2ac7773c-1026-49a4-a726-edcbcdf06a4b.png)
![Size_After](https://user-images.githubusercontent.com/107225715/178084542-940f7e1a-8d6b-48b2-9e5e-f5b3f6962198.png)

Thomas High School falls into the Medium(1000-1999) school size so that bracket  has been affected as shown above.



* **Affect on Scores by School Type Before and After:**

![Type_Before](https://user-images.githubusercontent.com/107225715/178084551-2ac152a8-a829-4c39-8632-fa5f966fd09f.png)
![Type_After](https://user-images.githubusercontent.com/107225715/178084553-36a0dc87-6258-4b11-8f99-78eb38626fec.png)

Since Thomas High School is a Charter type high school, that bracket is affected by around 0.04 percent overall.


## Summary

Unfortunately, there is no way of determining how much this slight change has affected the overall budget allotment of all the schools in the district but from our analysis we can summarize the affect it had on the numbers. The district summary was affected by 0.1 percent which does not seem like a significant change considering there were only 461 students in the Thomas High School ninth grade and the total school count was 39170. Looking over the schools summary, only Thomas High School's performance was affected and decreaced by around 0.4 percent overall. The schools remained at their same ranking even after changes in the numbers and Thomas High School remained in top 5 schools. Only change in the math and reading scores was that the Thomas High School 9th grade scores were replaced with NaNs. Looking at the numbers for spending, size, and type, they were affected very minimaly in the spending range $631-645, size category Medium(1000-1999), and school type charter. 










