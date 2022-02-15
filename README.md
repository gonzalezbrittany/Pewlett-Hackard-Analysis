# Pewlett-Hackard-Analysis

## Overview of the analysis: 
Pewlett Hackard has several thousand employees, many of which are baby boomers who will be retiring soon. The company offers retiring packages for those who meeting certain criteria. Pewlett Hackard is prepping for those who will be retiring and would like a list showing who is retiring and how many positions need to be filled. SQL is utilized to create a company database and break down the data to answer these questions. Further analysis was then completed to find how many employees will be retiring per title and how many of these qualify for the mentorship program.

## Results:
To begin the analysis a table was first created to show all employees listed within the company, the beginning of the table is presented below.

![image](https://user-images.githubusercontent.com/26393180/153972130-30bb757a-2ca3-4980-bdf2-61a5a7ad56dc.png)

After evaluating the table, it’s apparent that there are a few issues that need correcting.
* Some employees are listed multiple times due to promotions.
* Some listed employees do not currently work for the company, therefore, no preparation for position replacement needs to be completed. These employees will need to be removed.

The issues mentioned above had been corrected. The below table presents the beginning of the updated listed of all current employees that will be retiring soon. 

![image](https://user-images.githubusercontent.com/26393180/153972251-9195b941-0691-4566-a513-4d085e1ba262.png)

This list of all currently employees that will be retiring shows there are 72,458 employees whose positions will need to be filled.

This table was then grouped by job title.

![image](https://user-images.githubusercontent.com/26393180/153972365-847ccc66-297d-4afd-8f98-e29c88090911.png)

The above table helps paint a clearer picture on how different areas will be affected.
* Senior Engineer and Senior Staff positions have the most current employees that will be retiring.
* Manager positions have the least current employees that will be retiring.

A list of retiring employees that are eligible for the mentorship program ,those born in during the year 1965, was also created. The beginning of the dataset is presented below.

![image](https://user-images.githubusercontent.com/26393180/153972506-0a8ee946-a686-44f7-8eb4-37d5d9463393.png)

Theis dataset shows only 1,549 of the currently retiring employees are eligible for the mentorship program. 

## Summary

Our analysis helps present a picture of how Pewlett Hackard will be impacted by the upcoming retiring surge. 

* The data shows that the upcoming retiring “silver tsunami” group will include 72,458 current employees. All these positions will need to be filled

  ![image](https://user-images.githubusercontent.com/26393180/153972619-591728ed-a4cd-41a1-9d36-d72d07eeeb38.png)
  
* After seeing how many retiring employees qualify for the mentoring program. The chart below shows the count of how many mentors per title will be available. The middle count column shows how many mentors are available while the far-right count column shows how many overall positions will need to be filled for that title. 

  ![image](https://user-images.githubusercontent.com/26393180/153972756-2a784181-e793-4569-b636-003bbf506059.png)

  The table shows all titles have far less mentors compared to how many overall positions will need to be filled. This could be problematic during the transition. 

