# kickstarter-analysis
Performing analysis on kickstarter data to uncover trends 

Thomas Sheridan
31 July

### Challange 1 'Kickstarter Analysis"

## Overiview of Project

Our Client Louise, wants to know how different campaigns faired in relation to their launch dateand funding goal. I was assigned to create data based on outcomes based on launch date and outcomes based on goals. Through this project I was able to conclude for the client which Plays were successful, failed and cancelled by month as well as successful, failed and canceled. 

## Purpose of project

The purpose of this project was to show the client, Louise how different endeavors resulted in relation to their start date. I was provided historical data and using analytics and visualation tools was able to produce a deliverable that showed the client how each the outcome of how each endeavor fared based on its launch date and its goal. 

## Analysis and Challenges

This deliverable consisted of two analyses, one being an outcome based on goal and on being an outcome based on launch date. 
To generate the deliverable of ‘outcome based on goal’ Microsoft Excel and its tool PivotTable was used, with its challenge being able to properly populate the PivotTable field in order to present the data in the most user-friendly style for consumption.  
To generate the deliverable of ‘outcome based on launch date’ Microsoft Excel was used again, this time with a table being the tool used to generate the visitation. The challenge of this was creating the COUNTIFS function to filter through the data to fit in the requested parameters.  

### Analysis of Outcomes Based on Launch Date

In the Outcomes Based on Launch Date deliverable the first step was using Microsoft Excel and adding in an addiotnal row of data which returned the Year was performed, which was pulled from the Date Created Converstion column. Secondly, a PivotTable was created and was filtered with Parent Category and Years followed by Outcomes as the column. My next step was to add Month to the rows section and finally use count of Outcomes as the value.  

### Analysis of Outcomes Based on Goals

In the Outcomes Based on Goals deliverable the first step was to create a column in which the monetary goal was broken down into digestible ranges. The next step was to use the COUNTIFS function in order to deduce if the result was successful, failed or canceled. The next field in the COUNTIF function was only pulling Plays and then finally only counting the plays that fell in the monetary range for said row. After the data was counted, I used mathematical formulas to create the percentage of each play what was successful, failed or canceled with each monetary goal range. I then created a line chart as to aid as a visual tool for the client. 

### Challenges and Difficulties Encountered

The primary challenge I encountered during this exercise was getting the correct COUNTIF function on the Outcomes Based on Goals deliverable. I was able to solve this problem by using open source excel resources and watching tutorials on COUNTIFS as well as reading the help section on Microsoft Excel Support. 

The second challenge I faced was filtering the PivotTable with the correct Rows/Columns/Filters and Values to generate the chart the client was looking for. I was able to solve this with trial and error. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The first conclusion I can draw from the Outcomes based on Launch date is that the endeavor is most likely going to be successful if it is launched in May or June. The least likely successful launch month is December. 
The second conclusion drawn is that there are more successful endeavors in theater then failed, and more failed endeavors than canceled. 


- Regarding the Outcomes based on Goals:

There were  no cancelled outcomes of Plays. 
The second conculusion is that if the plays goal was less than 4999 it has the highest probability of being successful. 

One limitation of this dataset is that there was very few plays with a goal of greater then 20,000, with it being 21 and under 20,000 being 673. 
