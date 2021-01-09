# Starbucks-Reward-App-Capstone-Project 

# Udacity Data Scientist Nanodegree Capstone Project

This repository has all the code and report for my Udacity Data Scientist Nanodegree Capstone project.

## Starbucks Capstone Challenge: Using Starbucks app user data to predict effective offers

## Table of Contents
1. [Installation](#installation)
2. [Introducing a Dataset](#dataset-introduction)
3. [Project Motivation](#project-motivation)
4. [File Descriptions](#files)
5. [Results](#results)
6. [Licensing, Authors, Acknowledgements](#license)

### Installation <a name="installation"></a>
For running this project, the most important library is Python version of Anaconda Distribution. It installs all necessary packages for analysis and building models. 

### Introducing a Dataset <a name="dataset-introduction"></a>
This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.

Not all users receive the same offer, and that is the challenge to solve with this data set.

### Project Motivation <a name="project-motivation"></a>
In this project, I use the data to answer 2 business questions:

 __Part 1: Main Focus__
Combine transaction, demographic and offer data to determine which demographic groups respond best to which offer type. How does the following influence the use of the Starbucks offer rewards:

- Age
- Income
- Gender

After analyzing the demographics we will have a better understanding of what offer types are popular. 

__Part 2: Main Focus__
Build a machine learning model to predict the accuracy of offers completed from the EDA of part 1.

To answer the above 2 questions, I created 3 models for the data on the 3 offer types provided. The three offers are: Buy One Get One Free (BOGO), Discount (discount with purchase), and Informational (provides information about products).

### File Descriptions <a name="files"></a>
This repo contains 4 files.There is a notebook available here to showcase work related to the above questions and wrangling process. There are 3 data files used to address the above qustions
1. portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
2. profile.json - demographic data for each customer
3. transcript.json - records for transactions, offers received, offers viewed, and offers completed

## Results<a name="results"></a>

As a brief summary of my findings:


The main observations of the code are published.

### Licensing, Authors, Acknowledgements, etc.<a name="license"></a>

Data for coding project was provided by Udacity.


