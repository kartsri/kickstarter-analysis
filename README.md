# Module 1 Challenge: Kickstarting with Excel
## Overview of Project
The purpose of this analysis was to understand how different campaigns fared in relation to their launch dates and their funding goals, using skills we've learned in Excel.
## Analysis and Challenges
I performed the first component of the analysis by creating a Year column in the Kickstarter sheet. Then, I created a Pivot Table and filtered by Parent Category to assess how the launch date (by month) affected theater outcomes. A challenege that occured was visually assessing the gap in the canceled data - however, this is simply because no canceled Theater projects were launched in the month of October.


![image](https://user-images.githubusercontent.com/88801411/130373264-9ef8caa9-4351-47de-9d48-9223d5d77f76.png)


I performed the second component of the analysis by creating a new table using the COUNTIFS forumula. This analysis tracked outcomes based on goals with different breakpoints. I initially was challeneged in figuring out the correct syntax for this formula, but realized I should use quotation marks to ensure the criteria is properly logged.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/88801411/130373320-63878bf5-c2f2-4c5e-ab85-53ee6af15131.png)

## Results
Two conclusions that can be drawn from Theater Outcomes by Launch Date: First, very few Theater projects (less than 3%) are canceled - they are typically either successful or fail. Second, the warmer months tend to result in more successful Theater Outcomes than the colder months (May - July was very succesful compared to October - December).
A conclusion to be drawn from Outcomes Based on Goals is that projects with Goals over $45,000 as extremely likely to fail, in comparison to other ranges. Projects with goals under $5,000 are the most likely projects to succeed.
Limitations of the dataset could be that there may be more information to conclude by analyzing data outside of just the Kickstarter platform, if one is wanting to assess the success of independent Theater projects overall. Additional graphs/tables that could be helpful include Outcome by Duration (this could be a caulculated column using Launch and Deadline).
