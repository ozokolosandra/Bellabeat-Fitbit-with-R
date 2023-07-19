# Bellabeat-Fitbit-with-R
Bellabeat company
Bellabeat is a successful small company, but they have the potential to become a larger player in the global smart device market. Urška Sršen, cofounder and Chief Creative Officer of Bellabeat, believes that analyzing smart device fitness data could help unlock new growth opportunities for the company. You have been asked to focus on one of Bellabeat’s products and analyze smart device data to gain insight into how consumers are using their smart devices. The insights you discover will then help guide marketing strategy for the company. You will present your analysis to the Bellabeat executive team along with your high-level recommendations for Bellabeat’s marketing strategy.

Stakeholders
Urška Sršen: Bellabeat’s cofounder and Chief Creative Officer
○ Sando Mur: Mathematician and Bellabeat’s cofounder; key member of the Bellabeat executive team
○ Bellabeat marketing analytics team.


Data Analysis phase
1.Ask 
  Lets re-define the questions
  What are the problems we are trying to solve?
    a. Whar are the trends in the usage of the Fitbit Tracker?-- 
    b. How can the insights drive business decisions?--

    
2.Prepare
    a.What kind of data are we using?--Thirty fitbit users shared their personal logs
    b.Where are we getting the data from?--The data was gotten from kaggle through through Mobius.
    c.Does the data follow ROCCC format? The data is limited. It contains only data of two months. Also, the users are also small
    ,since Bellabeats just want to get an idea of fitness market.

    
 3.Process
     a.we need to clean the dataset by formatting the column names
     b.And also,filter duplicates and missing values.
     c.We will be using R to process and visualize our data.

     
  4.Analyze
      a.We discovered that people tend to do more activities on Tues,Wed and Thurs.
      b.We also discovered that 33 persons use the Fitbit Tracker to track daily_activity,daily_steps,steps_hour
       ,24 people used it to track their sleep,14 people used to track heart rate and 8 people used it to log their weight.
       c.We noticed a high average daily step in April 27,and we cannot deduce the cause for eg, was it a world health day? or fitness etc

       
 5.Share
  a.We used line charts,column charts and bar charts to share our findings
  b.We also checked the correlation between Total time in bed and total time asleep, we discovered a strong positive correlation.
  c.we took it further to check the p_value and found out that there is a strong statistical significance.
  d.We used a scatter plot to find out the number of days people worked out Vs average steps, there was a mild relationship.
  e.We also saw the peak periods when people track their steps hourly;eg morning at 10:00 and evening from 7:00pm.

  
  6. Act
  From my finding I will recommend the following to stakeholders;
  a. Marketing Team should roll out features that will help people to work out more from Tues till Thurs.
  b.They should also encourage users to track their steps between 10 and 7pm, and from thr look of this, majority of our usesr are 9 to 5 office workers.
  c.The average steps per day is 5000steps per day and this should be used to encourage the users.
  d.The team should focus on people that use the Tracker for daily activities, daily steps and hourly steps. A further analysis should be done in order to find out why the other users are not as active as the users mentioned above.
  e. Add features that will help users in bed to focus on sleeping by putting their phones away or in idle mood.
  
  
  
     
  
