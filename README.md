# FBI-Gun-Data

FBI GUN DATA : The data comes from the FBI's National Instant Criminal Background Check System. The NICS is used by to determine
whether a prospective buyer is eligible to buy firearms or explosives. Gun shops call into this system to ensure that each customer does not have a criminal record or isn’t otherwise ineligible to make a purchase. The data has been supplemented with state level data from


The Questions I posed
1.What is the best state in selling guns
2.Is population number and poverty has impact on selling guns in each state
3.Is number of veterans has impact on selling guns

Description of what I did to answer those questions
I tried to clean the data as much as possible by finding missing values and outliers and recreated it by taking just the usefull Columns. And I answered the first question by grouping my data with state and sum the selling guns
For census data it was very tricky cause the state was in columns and the rows was the parameters about the state so I chose to use transposing and I merged the gun data and census data
I answered the second question by creating a new dataset which has columns from census data as population and poverty percent and gun data as years and Totals .
I chose data guns from 2010 to 2016 with population columns and poverty columns , I plotted the totals guns and population and poverty to see is those parameters have any effect about Guns selling I answered the third question by creating a new dataset which has columns from census data as veterans and gun data as years and
Totals .
