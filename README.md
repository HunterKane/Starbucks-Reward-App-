# Starbucks-Capstone-Project
This is a capstone project for the course completed in response to Udacity- Data Scientist Nanodegree Program.   
Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.
Not all users receive the same offer, and that is the challenge to solve with this data set.   
Main task is to combine transaction, demographic and offer data to determine which demographic groups respond best to which offer type.
You can find the blog post link here [MEDIUM-BLOG](https://hunter-kane-sparrow.medium.com/starbucks-capstone-challenge-5e3d282fc231)
## Table Of Contents  
* [Motivation](#motivation) 
* [Prerequisites](#prerequisite)
* [Summary](#summary)  
* [File Description](#description)  
* [Acknowledgement](#acknowlegments)  
* [Running the Application](#running)  


<a name="motivation"></a>
## Motivation
The motivation behind this project was exploring the Starbuck’s Dataset. I explored the data to discover the following:

* What are the total amount of offers?
* What product(s) have the highest rank?
* What types of offers to genders prefer? (What are the percentages of gender in the data?)
* What is the age range that completes the most offers?
* What is the income ranges of customers? (age and gender)

<a name="prerequisite"/></a>
## Prerequisites
* Python
* VsCode
* Jupyter Notebook
* Pandas
* Numpy
* Matplotlib
* Anaconda
* Seaborn
* Json
* Sklearn model selections
* ProgressBar
* Sklearn.metrics 
* Matplotlib patches
* os
* sys
* Sklearn tree, Naive bayes, ensemble
* itertools

<a name="summary"></a>
## Summary 
The project was completed in the following phases:

__Part 1: Main Focus__
Combine transaction, demographic and offer data to determine which demographic groups respond best to which offer type.
- Inspect 
- Clean 
- Analyze

__Part 2: Main Focus__
Build a machine learning model to predict the accuracy of offers completed from the EDA of part 1. 
- Model data 
- Test 3 different models 
- Tune one model to improve results 
- Conclusion on what should be done to better improve performance results  

<a name="description"></a>
## File Descriptions
#### Data Dictionary
##### profile.json
Rewards program users (17000 users x 5 fields)
- gender: (categorical) M, F, O, or null   
- age: (numeric) missing value encoded as 118   
- id: (string/hash)   
- became_member_on: (date) format YYYYMMDD   
- income: (numeric)      

##### portfolio.json
Offers sent during 30-day test period (10 offers x 6 fields)
- reward: (numeric) money awarded for the amount spent   
- channels: (list) web, email, mobile, social   
- difficulty: (numeric) money required to be spent to receive reward   
- duration: (numeric) time for offer to be open, in days   
- offer_type: (string) bogo, discount, informational   
- id: (string/hash)     
 
##### transcript.json
Event log (306648 events x 4 fields)
- person: (string/hash)   
- event: (string) offer received, offer viewed, transaction, offer completed   
- value: (dictionary) different values depending on event type   
- offer id: (string/hash) not associated with any "transaction"   
- amount: (numeric) money spent in "transaction"   
- reward: (numeric) money gained from "offer completed"   
- time: (numeric) hours after start of test   

<a name="acknowlegdements"/></a>
## Acknowledgement
This project was made possible by Udacity allowing us the access to the dataset. 

<a name="running"/></a>
## Running the Application
In order to run the project, you can find the ipynb notebook file in the project directory which you can run directly, Make sure to keep the data set in the data folders, if the data location is changed, make sure to reflect the changes in the import section of the notebook file with necessary adjustments.   
In addition to this, you can also find the .html file in the project directory to take a quick glimpse of the project too.
