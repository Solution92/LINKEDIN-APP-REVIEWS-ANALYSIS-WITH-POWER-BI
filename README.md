# LINKEDIN-APP-REVIEWS-ANALYSIS-WITH-POWER-BI

## Table of Content
- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Data Sourcing](#data-sourcing)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [The Dashboard](#the-dashboard)
- [Result and Findings](#result-and-findings)
- [Recommendation](#recommendation)


### Introduction

LinkedIn (/lɪŋktˈɪn/) is a business and employment-focused social media platform that works through websites and mobile apps. It was launched on May 5, 2003. Since December 2016, it has been a wholly-owned subsidiary of Microsoft. The platform is primarily used for professional networking and career development and allows job seekers to post their CVs and employers to post jobs. From 2015 most of the company's revenue came from selling access to information about its members to recruiters and sales professionals. LinkedIn has more than 970 million registered members from over 200 countries and territories.
These reviews were extracted from its Google Store page.

### Problem Statement

- Identify which version of the app had the most positive feedback.
- Analyze Autor App Reviews
- Which version of the app had the worst feedback?
- Pinpoint customer Review Percentage

### Data Sourcing

The dataset was extracted from [Kaggle](https://www.kaggle.com/datasets/bwandowando/320k-linkedin-app-google-store-reviews)

### Data Cleaning and Preparation

The dataset had over 1000 rows and 9 columns with some column headers as Author_NAme, Review_text_use, Review_Rating, Review_Like, etc.

Some of the Transformation Processes where

_ Converted the timestamp column to the Date Column
- Created conditional column for Review column with categories like – 5- Very good, 4- Good, 3- Average, 2- Poor, 1- Very Poor
- Created a conditional column for author_app_version column with categories like 1st Version, 2nd Version,  3rd Version,  and 4th Version
- I created a Feedback_Category column to show “Positive” and “Negative” reviews. This is to help identify the most positive feedback and the worst feedback. This was done using the "Home" tab and clicking on the "Transform data" pane.

### The Dashboard

![Screenshot_177](https://github.com/Solution92/LINKEDIN-APP-REVIEWS-ANALYSIS-WITH-POWER-BI/assets/144762124/0b1c5441-0fb5-4867-81c4-d8a9009909db)

### Result and Findings

- In the feedback Category, Positive Feedback was 79.81% which is about 3000% over the Negative Feedback given 20.19%. Meanwhile, the majority of the positive feedback categories are within the 4th and 3rd Version of the Author App.
- At 168,790, the 4th Version had the highest Count of review ratings and was 1,842.35% higher than the 2nd Version, which had the lowest Count of review ratings at 8,690.  4th Version had the highest Count of review ratings  at 168,790, followed by 3rd Version, 1st Version, and 2nd Version.  4th Version accounted for 66.97% of the Count of review ratings.  Across all 4 author app versions, the Count of review ratings ranged from 8,690 to 168,790.

### Recommendation

Based on the analysis, it is evident that the 4th Version of the app received overwhelmingly positive feedback, constituting 66.97% of the total review ratings. This suggests that users are highly satisfied with the latest version. 
However, negative feedback exists, particularly in the 1st Version, indicating areas for improvement. Therefore, it is recommended to focus on maintaining the positive aspects of the 4th Version while addressing specific concerns raised in the 1st Version to enhance overall user satisfaction.








