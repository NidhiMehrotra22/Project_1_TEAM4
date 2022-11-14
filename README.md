# UWA Data Analysis Bootcamp
## Project 1 - Team 4

### Overview
The term ‘job satisfaction’ has various meanings. There are many factors involved to measure or quantify this “satisfaction”. 
Our project has utilised the Glassdoor Job Reviews dataset from Kaggle to analyse the multidimensional sentiments of various job descriptions based on the ratings from 1 to 5 on different categories such as work-life balance, career opportunities,senior management and so on.

#### Dataset used
Glassdoor Job Reviews

Licence : [CC0: Public Domain]

Source : https://www.kaggle.com/datasets/davidgauthier/glassdoor-job-reviews

### Data Set Challenges 
Due to the size of this dataset, our greatest challenge was getting our Git Repo to work 
This dataset was full of NULL values, these needed to be replaced with 0
There were several columns in this dataset that were redundant and removed
As there are 427 companies in the dataset, analysing all companies across the various metrics was not possible in the time given

### Research Questions

#### Question 1
What is the relationship between the work environment factors and overall job satisfaction? These will include:
Work Life Balance
Career Opportunities
Diversity Inclusion
Company Benefits
Senior Management

#### Question 2
How has an employer's rating changed over the time period sampled, and what are the contributing work environment factors that may contribute to this change?

#### Question 3
Is there a correlation between the region an employee is working in and the overall job satisfaction across the companies sampled?

### Summary
#### Question 1
Calculated the Mean of the ratings of each factor and overall rating based on the firms 
compared the Bottom 5 and Top 5 Firms Overall Ratings vs their various work environment factors

Senior management rating is lower in the bottom five firms but this rating is higher in top five firms. Clearly, senior management have an enormous role to play in employees' engagement and commitment. 

It has also been found that there is no impact of Diversity inclusion as this factor has almost the same ratings in both cases.

#### Question 2
We selected two random companies to review and compare (The-LEGO-Group and Accenture)

We calculated the average score for each company by year, between 2008 to 2021 for Worklife Balance, Culture Values, Diversity Inclusion, Career Opportunities, Company Benefits and with our isolated focus being on Overall Rating.
The LEGO Group have a consistently high rating across all metrics and their employee satisfaction reviews are strong. Their peak was in 2020 at 4.37

Accenture display a much lower rate of employee satisfaction however have made a huge improvement over the rating period with their peak also in 2020 at 3.88 and a slight dip in 2021.

The dip during 2021 may have been impacted by the pandemic. It would be interesting to see the most recent reviews!

Interestingly, both companies had a very large decrease in 2011 and within a span of 2 years, made drastic improvements. This would lead us to believe an event of some kind occurred at this point in time. Perhaps the data sampling changed in 2011?

#### Question 3
We selected two random companies to review and compare (The-LEGO-Group and Accenture)

We calculated the average score for each company by location, for Work Life Balance, Culture Values, Diversity Inclusion, Career Opportunities, Company Benefits and with our isolated focus being on Overall Rating. 

We also looked at Work Life Balance and Culture Values together to see their effect on overall ratings for the locations.

We took the top 10 locations and bottom 10 locations for the two firms and plotted their various metrics

Senior Management is a factor in the rating of a location in the same way it is for overall job satisfaction 

Lower rated locations tend to have lower scores for Senior Management, where as the Higher rated locations have the opposite

On analysis, surprisingly we found that Work Life Balance and Culture Values do not play a pivotal role in a locations overall rating

In the case of Accenture, employees based overseas give a higher rating than those based in the UK

In the case of Lego, a low overall rating indicates that there will be low ratings across a majority of metrics sampled. This is not consistent with Accenture.


