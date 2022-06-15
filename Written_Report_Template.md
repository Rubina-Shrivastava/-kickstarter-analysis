# Kickstarting  challenge

##  Overview of  project
  Louise’s play Fever came close to its fundraising goal in a short amount of time. She wants to know how different campaigns fared in relation to their launch dates and their funding goals. Using the Kickstarter dataset, here we’ll visualize campaign outcomes based on their launch dates and their funding goals. 

### Purpose
To calculate and visualize the outcomes of sucessefull, canceled and failed based on launch date and goal.

## Analysis and Challenges
 We created two analysis: outcomes based on goals and outcomes based on launch date.
 To provide Louise with a visual summary of the data so that she can see the outcomes of  sucessefull ,canceled and failed and used one subcategory "plays" as criteria.

### Analysis of Outcomes Based on Launch Date
 For the purpose of this, we are using "Years" column, using the YEAR() function to extract the year from the “Date Created Conversion” column. And used excel graph to visualize campaign outcomes ("successful," "failed," and "canceled") based on launch date in form of months.

### Analysis of Outcomes Based on Goals 
 WE Created excel chart(s) to visualize the relationship between the goal-amount ranges on the x-axis and the percentage of successful, failed, or canceled projects on the y-axis. Also added "plays" as filter criteria to limit the results for plays only. 



## Challenges and Difficulties Encountered
### Analysis of Outcomes Based on Launch Date
Used "grouping" to group the "Row Labels" column to show the months of the year.  

### Analysis of Outcomes Based on Goals
Use COUNTIFS() functions to populate the "Number Successful," "Number Failed," and "Number Canceled" columns by filtering on the Kickstarter "outcome" column, on the "goal" amount column .i have to use  criteria in place of filter



## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

![Outcomess Based on Launch Date](https://github.com/Rubina-Shrivastava/-kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)


### Conclusion - (i) If we use play as creteria, then there is no cancelled outcomes.  (ii) Success is higher than failures. And (iii) in May, success rate at its peak.

- What can you conclude about the Outcomes based on Goals?

![Outcomess Based on Goal](https://github.com/Rubina-Shrivastava/-kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

### Conclusion - (i) If we use play as creteria, then there is no cancelled outcomes.  (ii) For certain ranges (5000 to 20000), the percentage of success if almost equal to failures.  However, for higher limits, the failures are more.

- What are some limitations of this dataset?

### 4000 rows seems less data to draw any long term conclusions.  This need to be validated with larger samples.

- What are some other possible tables and/or graphs that we could create?

### We can analysis other subcategories, other countries etc.