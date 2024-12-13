# HR Analytics

## Page 1
![HRA_1](https://github.com/user-attachments/assets/0c29e0c4-faba-4133-8d2a-7fe94c7cf708)


## Page 2
![HRA_2](https://github.com/user-attachments/assets/4a1be67e-2814-4a68-899a-346ed84f6e1e)



## Project Overview

### Business Problem
The business is facing a challenge with high employee attrition, which impacts overall productivity, increases recruitment costs, and disrupts team dynamics. This project aims to leverage data analysis to identify the underlying factors contributing to employee turnover. By uncovering these insights, the organization will be able to implement targeted strategies to reduce attrition rates and improve employee retention, ultimately creating a more stable and productive workforce.

### Insights and Recommendations
#### 1. High Attrition Rate (50.21%)
   The current attrition rate stands at 50.21%. To effectively mitigate this, it is crucial for management to address all underlying employee concerns                  comprehensively. A proactive resolution of these issues will be key to significantly lowering turnover rates.
#### 2. Work-Life Balance Disparities
   Certain departments and job roles exhibit notably poor work-life balance, which has emerged as a major factor contributing to employee attrition. Improving work-    life balance within these areas will play a critical role in retaining employees and curbing mass departures.
#### 3. Targeted Performance Improvement
   Departments with lower performance ratings can see substantial improvement through targeted training initiatives and enhanced managerial support. By investing       in these underperforming areas, the organization can drive overall performance and productivity improvements.
#### 4. Compensation Structure Optimization
   Aligning salary structures with employee experience and implementing performance-based incentives will significantly enhance employee satisfaction. This, in         turn, will lead to stronger retention rates and a corresponding decrease in attrition.
#### 5. Minimizing the Impact of Overtime
   Extended overtime has shown limited positive impact on overall performance, with departments like Sales experiencing noticeable declines in output. To safeguard     performance, it is recommended that overtime be strategically minimized, especially in high-impact areas.
#### 6. Enhancing Career Development through Business Travel
   Employees who do not engage in business travel are more likely to leave the organization, likely in search of greater professional growth and exposure               opportunities elsewhere. Offering expanded travel opportunities to employees aspiring for career progression can significantly improve retention and reduce          attrition.
#### 7. Timely Promotions for Long-Tenured Employees
   A discernible trend indicates delayed promotions for long-tenured employees, which can negatively affect morale and contribute to higher attrition rates. To         counter this, management should prioritize timely promotions for these employees, ensuring they feel valued and incentivized to remain with the organization.

## Detailed Analysis

### Data source
Dataset: The dataset used for this Analysis is the HR Data.csv file

### Tools 
Excel, Power BI

### Data cleaning
The following steps were performed in the Data cleaning phase on the Power Query Editor:
 1. Loading the data
 2. Changing the data types of certain variables
 3. Handling missing values and duplicates
 4. Merged the 2 data sets into a single sheet using Merge Queries to create a single data sheet
 5. Data cleaning and formatting

### Data Analysis
The Data analysis process delivered the following insights:

#### 1. Attrition Rate

The current attrition rate stands at 50.21%. To effectively reduce this rate, it is essential for management to proactively address and resolve the concerns and issues faced by employees

#### 2. Department wise Total Employees

![Dept wise Total Employees](https://github.com/user-attachments/assets/f9e6ad29-7493-4833-bda6-f3a51071ffa5)

The donut chart above displays the total number of employees in each department, along with their percentage share of the organization's workforce.
* Insights:The distribution of employees across departments is relatively uniform, with each department comprising approximately 16-17% of the total workforce.
* Departments like Sales, Human Resources, and Software have slightly higher employee counts than others, which may indicate their critical role in the organization.
* The even distribution suggests balanced hiring policies or equivalent workforce needs across departments.

#### 3. Overtime vs Performance Rating

![Overtime vs Performance Rating](https://github.com/user-attachments/assets/23c510d7-e7f9-431f-ab7b-b05daebf65ad)

* The line chart above represents the relationship between Overtime and Average Performance Rating across different departments or job functions: Hardware, Human Resources, Research & Development, Sales, Software, and Support.
* No Overtime: Performance ratings in all departments with No Overtime seem to hover around a similar range (between 2.49 and 2.51). The departments Software (2.51) and Support (2.50) show slightly higher average performance ratings, while Sales shows a relatively lower rating of 2.49.
* Yes (With Overtime): When overtime is present, there's a notable variation: Sales shows a significant drop in performance rating (from 2.49 to 2.46). Research & Development, Support, and Software show slight improvements, with Support having the highest rating (2.52) among all. Hardware remains relatively stable, with a marginal increase in rating from 2.50 to 2.51.
* Insights: In some departments like Sales, overtime appears to have a negative impact on performance ratings, whereas in departments like Support and Software, it slightly boosts the performance rating. Departments like Hardware and Human Resources show little variation in performance ratings regardless of whether employees are working overtime or not

#### 4. Overall tenure at the company
  
![Overall Tenure at the Company](https://github.com/user-attachments/assets/8090a921-fa8f-4e9f-8a0d-b037c54cd465)

* The line chart above illustrates the average overall tenure of employees across various departments in the organization.
* Insights:Employees in the Sales department have the highest average tenure (10.84 years), indicating either high job satisfaction or lower turnover in this department.
* The Research & Development department shows the lowest average tenure (10.68 years), which might highlight challenges in retaining employees in that department.
* The tenure differences across departments are relatively small, suggesting that overall employee retention strategies may be consistently effective across the organization.

#### 5. Attrition vs Distance from home

![Attrition vs Distance from Home](https://github.com/user-attachments/assets/e4934d01-17c7-4925-874c-1753506f7899)

* The line chart above illustrates the influence of Distance from home on the Attrition rate
* Attrition Count Analysis: The attrition count exhibits significant fluctuations across varying travel distances.
* Peaks Observed: Notable peaks in attrition count are identified at distances of 10 (525), 20 (547), 30 (540), 40 (541), and again near 50 (539).
* Lowest Count: The lowest attrition count occurs at a distance of approximately 40, with a total of 463.
* Insights: This graph suggests that employee attrition rates are influenced by the distance employees must travel from their homes, indicating a potential correlation between travel distance and attrition levels

#### 6. Job Role wise average work life balance

![Job Role wise Average Work Life balance](https://github.com/user-attachments/assets/0702d8d2-d344-46f6-a3ba-7ceea603d749)

* The area chart above represents Job Role wise Average Work Life Balance
* Highest Work-Life Balance: Research Scientists exhibit the highest average work-life balance score, measured at 2.514
* Lowest Work-Life Balance: Sales Executives demonstrate the lowest average score, at 2.469
* Insights: There is a discernible decline in work-life balance from Research Scientists to Sales Executives, indicating a progressive decrease in work-life satisfaction across these roles

#### 7. Department wise Average performance rating
   
![Dept wise Average Performance Rating](https://github.com/user-attachments/assets/e33827a3-adba-492b-99f7-52470d245cfb)

* The line chart above represents the Department wise Average Performance Rating
* Highest Performance: The Research & Development department achieves the highest average performance rating of 2.51
* Lowest Performance: The Sales department records the lowest performance rating at 2.48
* Insights: There is a marginal decline in performance ratings, moving from departments such as Support, Hardware, and Software (all at 2.50) to Human Resources and finally to Sales
* The chart emphasizes the need for strategic focus on departments with lower performance ratings, particularly Sales and Human Resources, to enhance overall departmental performance

#### 8. Training time vs performance rating
   
![Training time vs Performance Rating](https://github.com/user-attachments/assets/1bc6d9f5-d3a0-4a1c-9af7-f65c43eaa603)

* The scatter plot above represents the Training time vs Average Performance rating
* Training Duration: Training time varies from 1 to 6 hours.
* Performance Ratings: Performance ratings are relatively clustered within the range of 2.46 to 2.52.
* Insights: The data points suggest a slight upward trend in average performance ratings as training time increases, with the highest rating observed at approximately 2.52 for a training duration of 6 hours.
* The chart implies that employees who invest more time in training tend to achieve marginally higher performance ratings, although the variation in ratings is minimal

#### 9. Department wise average stock options

 ![Dept wise Average stock option](https://github.com/user-attachments/assets/75339b74-25cb-49b7-88e3-53f6280a4e59)

* This pie chart above displays the distribution of stock options granted to employees across various departments within the organization.
* Insights: The distribution of stock options appears relatively balanced across departments, with each segment contributing approximately equally to the total.
* Slight variations exist, such as the Research & Development department potentially receiving a slightly larger share of stock options.
* This balanced distribution might reflect equitable company policies in stock option allocation, fostering employee motivation and satisfaction across all departments.

#### 10. Department wise Attrition rate

![Dept wise Attrition Rate](https://github.com/user-attachments/assets/053ce41b-177b-430b-8902-5bf657a988e6)

* The above chart represents the Department wise Attrition
* Highest Attrition: The department with the highest attrition rate is Research & Development with 31.14%. This could indicate challenges specific to this department, such as work pressure, lack of engagement, or dissatisfaction among employees.
* Lowest Attrition: The Sales department has the lowest attrition rate at 15.71%. This suggests employees in the Sales department may be more satisfied or the job role is better aligned with their expectations.
* Medium Attrition: The Human Resources (20.33%), Software (23.93%), and Support (20.11%) departments show moderate attrition rates. These numbers are not as concerning as Research & Development but still merit attention for further analysis.
* Trends: The attrition rate fluctuates significantly across departments. For example, the sharp spike in Research & Development is notable compared to the relatively stable or lower rates in other departments.
* Departments with lower attrition, such as Sales, may be using retention strategies that could be implemented elsewhere.

 #### 11. Department wise Average Job satisfaction

![Dept wise Average job satisfaction](https://github.com/user-attachments/assets/f69336ac-e440-4523-bf85-d41a69b61f29)

* The above chart represents the Department wise Average job satisfaction levels with a declining trend. Here are some insights based on this visual
* Highest Job Satisfaction:  The Research & Development department has the highest average job satisfaction level at 3.31. Despite this, the earlier attrition chart showed that this department has the highest attrition rate, indicating a possible disconnect between job satisfaction and other factors (e.g., workload, pay, or growth opportunities).
* Lowest Job Satisfaction:The Software department has the lowest job satisfaction score at 2.46, which aligns with its moderate attrition rate (23.93%). This suggests dissatisfaction might stem from specific issues like work environment, tasks, or management.
* Steady Decline: The trend shows a continuous decrease in job satisfaction levels across departments as we move from Research & Development to Software. This indicates that satisfaction factors may be department-specific or tied to the nature of the work.
* Moderate Satisfaction: Departments like Support (2.90) and Sales (2.69) show average satisfaction levels. While not the lowest, these scores still highlight room for improvement.

 #### 12. Salary hike vs Job satisfaction

![Salary hike vs Job satisfaction](https://github.com/user-attachments/assets/e5b0f17d-0f56-482f-9a35-d3f0ab8d89c5)

* The above chart represents job satisfaction levels vs. percent salary hike, showing a scattered and fluctuating relationship. Here are some insights based on the visualization
* Inconsistent Relationship: There is no clear linear trend between job satisfaction and percent salary hike. For example, at certain points, a higher salary hike correlates with higher job satisfaction, but at other points, the satisfaction level drops despite an increase in the salary hike.
* Peaks in Satisfaction: Highest job satisfaction is around 3.89, corresponding to a specific salary hike (possibly near 20%). This indicates that certain salary hikes may significantly boost satisfaction.
* There are multiple peaks, suggesting that job satisfaction might be influenced by additional factors besides salary hikes (e.g., work environment, management, or career growth).
* Valleys in Satisfaction: Some of the lowest satisfaction levels, around 2.0–2.5, occur at various points on the salary hike axis. This suggests that salary hikes alone do not guarantee satisfaction and other issues might overshadow the effect of compensation increases.
* Fluctuation: The jagged nature of the graph highlights the variability in how employees perceive salary hikes. This may point to differing expectations, fairness perceptions, or satisfaction drivers across employee groups.

#### 13. Department wise Age distribution

![Dept wise Age distribution](https://github.com/user-attachments/assets/4cf5aa26-03e1-43a6-b19b-8b8f02920826)

* The above chart depicts department-wise average age distribution across various departments in an organization. Here's an analysis based on the visual
* Trends in Age Distribution:
  * The average age is highest in the Hardware department (39.16 years).
  * It slightly decreases across Research & Development (39.09 years) and Software (38.00 years).
  * A notable drop is seen in the Support department (34.46 years).
  * Human Resources and Sales departments have similar average ages at the lower end (both around 34.66 years).
* The Hardware department seems to have more experienced or senior employees compared to others.
* The Support, Human Resources, and Sales departments likely have a younger workforce, possibly indicating roles that attract early-career professionals or require less tenure.
* The gradual decline in average age from Hardware to Sales could indicate differences in the nature of work or experience levels required in each department.















 
