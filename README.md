# Classification Project: Predicting Gun Violence Injuries
## ADS-508 Cloud Computing

## Installation

1. Clone this repo
2. Run the following python Jupyter notebooks:
* Data_Preparation.ipynb
* 

## Partner/Contributors
* Vivian Do
* Kevin Baum
* Connie (Sau) Chow


### Company Name: BCD Healthcare
### Company Industry: Healthcare
### Company Size: 300,000+ Employees


## Methods
* Exploratory Data Analysis
* Data Preprocessing/Preparation
* Data Modeling & Evaluation Metrics

## Technologies
* AWS Sage Maker
* Jupyter Notebook
* Python
* SQL

## Abstract
The company’s hospitals are experiencing staffing shortages and overstaffing of ER nurses and physicians.  This is due to fluctuating patient admissions from local gun violence incidents.  The company would like to undertake a data science project to improve staffing accuracy, in terms of total staff count shifts, days of the week and months or holidays throughout the year in order to better serve the location population they reside in.


## Problem Statement
Gun violence has now been considered a public health crisis by many physicians. In addition to the enduring effects for victims and their families, there is a considerable toll on hospitals and health systems. According to the U.S. Government Accountability Office, hospital costs related to gun violence cost hospitals over $1 billion annually. Of that, $300 million are in charges to patients of gun violence with no insurance coverage—a cost that is ultimately absorbed by hospitals as uncompensated care (U.S. Government Accountability Office, 2021). 

To better serve our communities, we need to understand the areas and individuals who are most affected by gun violence. By looking at gun violence in different communities, hospitals can be staffed appropriately and expanded as needed. High-risk individuals can be identified and connected to community resources. As the leading provider of healthcare in the United States, we believe that it is our responsibility to address gun violence and secure the wellbeing of our communities. 


## Goals
Our main goal with our model is to find the areas of highest impact of gun violence. This will help achieve the following outcomes that can help the hospital’s business and standing in the public eye: 
Safeguard against under-staffing personnel at any given time: it is unsafe for patient safety to not have enough nurses and doctors at the hospital. With trauma cases, time is of the essence, and not having enough personnel to act quickly can be the difference between life and death of a patient.
Safeguard against over-staffing personnel at any given time: while this is fine for patient safety, the hospital needs to create a balance of over and under-staffing as nurses and doctors are expensive to employ. With too much personnel for the amount of patients there are, the hospital does operate as effectively as a business. 
Avoid low supply of trauma supplies: gunshot events require specific supplies, such as gauze to cover the wound. If supplies run out, the staff will be ill-equipped to do their jobs effectively. 
Avoid over-supplying trauma supplies: other types of medical emergencies, such as cardiac or stroke events, also require supplies specific to those types of incidents. If the hospital carries too much equipment for handling gunshot wounds, it may run out of critical supplies for other emergencies. 
Determine cities that may require additional overall staffing: the data will show locations, so the discovery of cities/areas that lack resources to handle trauma cases is possible with this data. If it is the case that the hospital is lacking personnel in an area that is highly afflicted with gunshot incidents, it must hire more staff. 
Gain more insight into gun violence for public health education: understand where the violence is happening and who the high-risk patients are, while considering programs as “next steps” at the conclusion of the project.


## Non-Goals
The KPI we are trying to measure here is the try to match 1-1 hospital staff to serve incoming ER patients as needed.  We want to decrease the % of ER staff that sits idle with respect to gun violence incidents.
We are not solving hospital budgeting and/or optimizing net profit or operating margins for the hospital location or overall business with respect to staffing hours and salaries or ambulatory costs and time spent traveling to hospital
We are not solving ER patient visit outcomes
We are not trying to solve the staffing problem with respect to general hospital ER admissions, we are only trying to solve it for the input of gun violence incidents victims that arrive at the hospital
We report prediction outcomes for only the cities involved in the main dataset containing gun violence figures
We do not make any distinction within the head count for staffing in terms of types of nurses or physicians.


## Data Sources
Describe where your source data will be coming from, and any risks you see given the data type, size, etc. Where will you store the data, how will it get there?
The dataset is sourced from the following GitHub repo: ​​https://github.com/jamesqo/gun-violence-data. The original data comes from the Gun Violence Archive, an “online archive of gun violence incidents collected from over 7,500  law enforcement, media, government and commercial sources daily in an effort to provide near-real time data about the results of gun violence. GVA is an independent data collection and research group with no affiliation with any advocacy organization” (Gun Violence Archive, n.d.).
Per the “about” section: It is “a comprehensive, accessible database that contains records of over 260k US gun violence incidents from January 2013 to March 2018.”
There are 104 CSV files containing information pertaining to months and years relating to the gunshot data. Many of the files contain more than 10,000 records, thus satisfying the data limit constraint of this project.
Approximate size of the data ranges from 1Mb to 5Mb. 
Our plan is to stay true to the purpose of this course and use AWS - therefore we plan to store the data in AWS S3. To do this, we will create buckets for the different files to get the data into S3.
One risk we foresee is managing the efficient use of this many different files. This will be the most files any of us have dealt with for a project, and we will need to set up loops in such a way as to operate as efficiently as possible, and not slow down/crash the program when the data is read into the program.


## References

# Presentation and Projects


