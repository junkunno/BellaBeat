# BellaBeat
BellaBeat Capstone Project

---
## "BellaBeat Case Study" <br>
## Author: "Dominique McIntosh"
## Date: '2022-03-16'

---


## How can insights into Fitbit user data be applied to BellaBeats *'Ivy'* Health Tracker? 

This source of the Fitbit user data recommended to be used can be found at [Kaggle](https://www.kaggle.com/arashnic/fitbit). The purpose of which was to see if insights could be gained into the user data which could help open up new opportunities for growth. In this instance, analysis was done with Bellabeats *'Ivy'* Health Tracker as the primary product to apply the insights to.
<br>
<img src="https://bellabeat.com/wp-content/uploads/2021/09/1-Bellabeat-Ivy-Garden-Jet-Black.jpg" width="200" height="200" />

## Summary of Data Source:
This source of the Fitbit user data recommended to be used can be found at [Kaggle](https://www.kaggle.com/arashnic/fitbit). 

* _30 Fitbit Users_ consented to the submission of their personal tracker data
* Data included information on sleep monitoring, heart rate, total steps, distance etc.
* The range of the data was 2 months of individual readings.

## Summary of Data Cleaning:
The data files were originally imported into Google Sheets & cleaned there. The process:

* 77 Rows of data were deleted due to incomplete information
* Duplicates were removed
* Data types & column headings were adjusted to create consistency
* Standard data cleaning routines applied: removing duplicates, trimming
* The _sleepDay_merged_ table was joined with the _dailyActivity_ to be able to anyalyse the data more effectively. 

## Limitations of the data to consider:

* Relatively small sample size.
* There were a few users in the study who had not worn their trackers at all, which can skew the results (they were ultimately deleted from the data sets)
* We don't know the gender or age of the users
* Results of analysis should just be a starting point for a deeper exploration into user habits

## Setting up the environment
Notes: seeting up the R environmnet by loading the following packages:

 * tidyverse 
 * ggplot2 
 * readr 
 * dplyr 
 * rmarkdown 
 

## Conclusions 
* The activity profile of the users are distributed fairly evenly across all profiles, with most users being moderately active.
* The more active the user was, the more calories they seemed to burn.
* There were more users getting less than 7hrs of sleep than any other sleep profile.
* The last data displays that the more active the user the less time spent sleeping.
* There were some instances where users inconsistently wore their trackers.

## Recommendations

* Consistency of use was also an issue, since the *Ivy Tracker* also monitors sleep, marketin campaigns should aslo be highliting the benefits of users understanding their sleep cycles by regularly wearing the device.
* In order for BellaBeat to encourage new and current customers to consistently wear their devices they can develop marketing campaigns to geared around challenges to reach certain activity levels by tracking their steps, having group competitions, users of the months etc. The goal would be to encourage users to increase their activity levels and the *Ivy Tracker* could help them to ensure they're meeting these goals. 
* Since the sleep data had to be merged with the daily activity table, it's likely that users had to wear more than one device, marketing could highlight the benefit of the convenience of wearing an all-in-one device that tracks multiple health data points.
* Considering the very small sample size I recommend that the company also conducts there own survey for their own users to find out amongst other things:
 * What made them choose their BellaBeat device?
 * Are they using their devices consistently?
 * What were their users hoping to accomplish based on the knowledge the devices give them about their own habits?
 * Are there additional health datapoints that they wanted to be able to measure? 
