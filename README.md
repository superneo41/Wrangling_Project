# Wrangling_Project

rpub.com/neo41/382968/


### 1. Problem   
Is there a relation between State Household Income, per capita Starbucks & per capita McDonald's ?  

The reason I came up with this question is because I observed that there are more students in Starbucks when it is finals week. People need coffee to stay focus on the study.    

So I wonder if people in one state consume more Starbucks coffee, does that means these people are more productive and make that state average income higher ? Similarly, what about McDonald's ?

### 2. Data
I obtained the average household income data and population data from the CENSUS using an API key.   

I scraped the starbucks stores data from StateMaster Website:  
http://www.statemaster.com/graph/lif_sta_sto-lifestyle-starbucks-stores#definition   

I download the McDonald's stores data from Statista Website:    
https://www.statista.com/statistics/631235/number-of-mcdonald-s-us-by-state/   

### 3. Approach
I try to visualize all the data.    

First I plot some maps showing the household income, number of Starbucks/McDonald's to get a rough idea about which states has the high income and which states has the most Starbucks/McDonald's stores.   

Then I fit a simple linear regression to see if income truely related to S/M (Starbucks/McDonald's).    

Finally, I analyse the regression model and get some insights.

