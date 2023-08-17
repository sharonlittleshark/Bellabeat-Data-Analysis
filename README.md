# Bellabeat-Data-Analysis
# Author: Sharon

## Introduction
This is a case project from Google Data Analytics Capstone in Coursera.

## Project Requirements
The project is a business task at Bellabeat. To unlock new growth opportunities, Bellabeat intend to increase their market shares in smart device market. Therefore, Fitbit(another smart device) fitness tracker data is used to gain insight into the trends in smart device usage. The full project introduction and requirements can be checked in the ***Case Study 2.pdf***.

## Data Resource
The [dataset](https://www.kaggle.com/datasets/arashnic/fitbit) used in this project is a public dataset on Kaggle, contains personal fitness tracker from thirty Fitbit users within a month with their consent.
The dataset included:
Daily Activity Data : included total steps, total distance, total calories, intensities within a day.
Hourly Activity Data : included total steps, total distance, total calories, intensities within an hour.
Minutely Activity Data：included total steps, total distance, total calories, intensities within a minute.
Others：included heart rate, sleep time and weight.

## Project Roadmap
#### Prepare
1.	Check and import the data.
2.  Figure out the preliminary trends in different function usage.
3.  Data cleaning.

#### Process
1.  Make the prediction.
  **H1**：User who are trying to lose weight will have higher daily activity intensity.
  **H2**:	User who are having more daily activities will have a better sleep quality.
  **H3**:	User who are having more daily activities will tend to use different functions.

2.  Select the variables to use in data analysis.
  **Activity**: Use TotalSteps, TotalDistances and Calories to represent the overall activity status of users.
  **Intensity**: Use VeryActiveMinutes and SedentaryMinutes to represent the detailed intensity status of users.
  **Sleep Quality**: Use TotalMinutesAsleep and SleepOnsetLatency(subtraction between in-bed duration and asleep duration) to represent the sleep quality of users.
  **Weight**: Consider the differences in gender, age and height among users, use BMI to represent users’ weight.
  **Frequency**: Count the frequencies of function usage among hourlyActivity, heartrate, weight and sleep Day datasets.

3.  Calculation.

#### Analysis and visualization
1. Descriptive analysis.
2. Relationship between weight, sleep quality and activity.

## Results and findings
**Functions usage frequency**
![image](https://github.com/sharonlittleshark/Bellabeat-Data-Analysis/assets/126043660/1ed9f4c1-75fb-4542-b013-e72a343abd7c)
**The correlation between variables**:
![image](https://github.com/sharonlittleshark/Bellabeat-Data-Analysis/assets/126043660/fef2daa5-1b68-4d67-8ed6-0cd81f43efe2)
**User characteristics**
**Activity**
![image](https://github.com/sharonlittleshark/Bellabeat-Data-Analysis/assets/126043660/aaee9d51-143a-4c94-8f0c-1b39d4502d05)
**Intensity**
![image](https://github.com/sharonlittleshark/Bellabeat-Data-Analysis/assets/126043660/5dd903b5-4b13-4a16-9ed7-18f6cb920af9)
**weight**
![image](https://github.com/sharonlittleshark/Bellabeat-Data-Analysis/assets/126043660/8ec2ec28-b715-4f35-a3c2-8f29c7a40398)
**sleep quality**
![image](https://github.com/sharonlittleshark/Bellabeat-Data-Analysis/assets/126043660/957a5d2d-77af-48d4-82d0-2e4d418b18d6)

**The mainly findings**:
1.	The popularity of function is following by the order: activity > sleep day > heart rate > weight.
2.	User activities shown a reasonable relationship: More activities burnt more calories and had healthier weight.
3.	Users who are trying lose weight will mention their weight and the heartrate function is useful for them.
4.	Users who use smart devices will overall having a high daily activities.

The full code and analysis process can be checked in the ***bellabeat - data analysis report.pdf***.
