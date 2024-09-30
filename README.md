# HR-Analytics
![Screenshot (926)](https://github.com/user-attachments/assets/6ebf79e2-b043-47e8-9118-7e87cd5559ed)

**Page 1**

![Screenshot (927)](https://github.com/user-attachments/assets/53827fbd-0b23-4bf9-9fef-3ce066f0a4fe)

**Page 2**

### Business Problem
The business is facing a challenge with high employee attrition, which impacts overall productivity, increases recruitment costs, and disrupts team dynamics. This project aims to leverage data analysis to identify the underlying factors contributing to employee turnover. By uncovering these insights, the organization will be able to implement targeted strategies to reduce attrition rates and improve employee retention, ultimately creating a more stable and productive workforce.

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

The current attrition rate stands at 50.21%. To effectively reduce this rate, it is essential for management to proactively address and resolve the               concerns and issues faced by employees

#### 2. Work Life Balance

![Work Life Balance](https://github.com/user-attachments/assets/6f2e1fc5-fd5b-414c-9b79-ce7bad4ad070)

* The area chart above represents Job Role wise Average Work Life Balance
* Highest Work-Life Balance: Research Scientists exhibit the highest average work-life balance score, measured at 2.514
* Lowest Work-Life Balance: Sales Executives demonstrate the lowest average score, at 2.469
* Insights: There is a discernible decline in work-life balance from Research Scientists to Sales Executives, indicating a progressive decrease in work-life           satisfaction across these roles

#### 3. Performance Rating

![Screenshot (909)](https://github.com/user-attachments/assets/250d72a8-9b50-4f4b-a253-bcca4ef5bc87)

* The line chart above represents the Department wise Average Performance Rating
* Highest Performance: The Research & Development department achieves the highest average performance rating of 2.51
* Lowest Performance: The Sales department records the lowest performance rating at 2.48
* Insights: There is a marginal decline in performance ratings, moving from departments such as Support, Hardware, and Software (all at 2.50) to Human Resources       and finally to Sales
* The chart emphasizes the need for strategic focus on departments with lower performance ratings, particularly Sales and Human Resources, to enhance overall          departmental performance

#### 4. Tenure
  
 ![Screenshot (910)](https://github.com/user-attachments/assets/1c6bcc8b-5419-4485-a2ce-9e77e75fc89f)

* The area chart above represents the Tenure of the employees at the organization
* There is a notable trend whereby the duration since an employee's last promotion tends to increase significantly with their tenure at the company:
* After 1 year of employment, the time since the last promotion is approximately 1 year
* After 10 years, this gap expands to approximately 5.94 years
* At the 30-year mark, the duration reaches 13.69 years
* By the time an employee has been with the company for 40 years, the gap extends to 22 years
* Insights: This trend suggests a potential delay in promotions for long-tenured employees, which may adversely impact morale and increase attrition if not            adequately addressed

#### 5. Performance wise Salary Hike

![Screenshot (911)](https://github.com/user-attachments/assets/f1340319-379d-412f-be59-338a0499dd03)

* The line chart above represents the Performance wise salary hike
* Highest Salary Hikes: The Human Resources and Research & Development departments report the highest percentage salary hikes, at 24.71%
* Low Salary Hikes: The percentage salary hike gradually declines through the Software (24.64%), Support (24.57%), Hardware (24.55%), and Sales (24.53%) departments
* Insights: There is a consistent downward trend in salary hikes across the various departments. This trend indicates that the Human Resources and Research &          Development departments provide higher average salary increases based on performance, while the Sales department offers the lowest percentage salary hikes


#### 6. Training time vs Average Performance Rating

![Screenshot (912)](https://github.com/user-attachments/assets/6c64555f-00cd-4b80-ab11-23d72782dfe9)

* The scatter plot above represents the Training time vs Average Performance rating
* Training Duration: Training time varies from 1 to 6 hours.
* Performance Ratings: Performance ratings are relatively clustered within the range of 2.46 to 2.52.
* Insights: The data points suggest a slight upward trend in average performance ratings as training time increases, with the highest rating observed at               approximately 2.52 for a training duration of 6 hours.
* The chart implies that employees who invest more time in training tend to achieve marginally higher performance ratings, although the variation in                   ratings is minimal.

#### 7. Attrition vs Distance From Home
   
![Screenshot (913)](https://github.com/user-attachments/assets/0b98262a-6aeb-41f1-912e-09857815f67d)

The line chart above delivers the following:
* Attrition Count Analysis: The attrition count exhibits significant fluctuations across varying travel distances.
* Peaks Observed: Notable peaks in attrition count are identified at distances of 10 (525), 20 (547), 30 (540), 40 (541), and again near 50 (539).
* Lowest Count: The lowest attrition count occurs at a distance of approximately 40, with a total of 463.
* Insights: This graph suggests that employee attrition rates are influenced by the distance employees must travel from their homes, indicating a potential            correlation between travel distance and attrition levels.
   
#### 8. Over Time vs Performance Rating 
   
![Screenshot (930)](https://github.com/user-attachments/assets/46ea2044-7bc5-467f-acea-5761e826b206)

* The line chart above represents the relationship between Overtime and Average Performance Rating across different departments or job functions: Hardware, Human      Resources, Research & Development, Sales, Software, and Support.
* No Overtime: Performance ratings in all departments with No Overtime seem to hover around a similar range (between 2.49 and 2.51).
  The departments Software (2.51) and Support (2.50) show slightly higher average performance ratings, while Sales shows a relatively lower rating of 2.49.
* Yes (With Overtime): When overtime is present, there's a notable variation:
  Sales shows a significant drop in performance rating (from 2.49 to 2.46).
  Research & Development, Support, and Software show slight improvements, with Support having the highest rating (2.52) among all.
  Hardware remains relatively stable, with a marginal increase in rating from 2.50 to 2.51.
* Insights: In some departments like Sales, overtime appears to have a negative impact on performance ratings, whereas in departments like Support and Software, it    slightly boosts the performance rating. Departments like Hardware and Human Resources show little variation in performance ratings regardless of whether employees   are working overtime or not.

#### 9.Attrition vs Business travel

 ![Screenshot (931)](https://github.com/user-attachments/assets/c5ba9865-ecdf-4ed7-bad7-95be396d7fbf)

* The clustered bar chart above illustrates the relationship between Attrition and Business Travel Frequency, with three categories: Non-Travel, Travel Frequently,    and Travel Rarely. The bar chart represents the Attrition Count for each category.
* Non-Travel:The highest attrition count is observed in the Non-Travel group, with a count of 16.92K. This suggests that employees who do not travel for business      tend to leave the organization more frequently compared to those who travel.
* Travel Frequently:Employees who Travel Frequently show an attrition count of 16.59K. Although this count is slightly lower than the Non-Travel group, it             indicates that frequent travel might be a contributing factor to attrition, though not as pronounced as the Non-Travel group.
* Travel Rarely:The Travel Rarely category has the lowest attrition count at 16.49K. Employees who travel occasionally for business seem to be less likely to leave    the organization compared to the other groups.
* Insights: Non-Traveling Employees Leave More: Employees who do not travel for business are more prone to leaving the company. This could imply that travel           opportunities or exposure might be a motivating factor for employee retention.
* Frequent Travelers: While frequent travel might lead to some degree of attrition, it appears less impactful than being in a role with no travel at all. However,     high levels of travel can still contribute to turnover, likely due to the potential for burnout or work-life imbalance.
* Occasional Travel Might Improve Retention: Employees who travel rarely seem to have the lowest attrition, which could suggest that occasional travel might strike    a balance between work engagement and avoiding travel-related stress.

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


   













 
