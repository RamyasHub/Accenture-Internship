# Accenture-Internship
This repository contains the tasks that has been performed during my Virtual Internship in Accenture.

# Overview
## The project requires to 
- Identify which datasets will be required to answer the client’s business question
- Clean the datasets and merge them to prepare the data for analysis
- Determine the answer to the client’s business question

## Data set
The client has provided with 
- 7 data sets and each data set contains different columns and values,
- A data model which shows the relationships between all of the data sets, as well as any links that you can use to merge tables.

## Steps in the project
### Requirements gathering 
            
The first step is to use this data model to identify which datasets will be required to answer the business question - which is to figure out the top 5 categories with the largest popularity
Its been identified Reaction, Content, and Reaction Types as our relevant data sets for the business requirements.
To clarify why this selection has been made,
- The client wanted to see “An analysis of their content categories showing the top 5 categories with the largest popularity”.
- As explained in the data model, popularity is quantified by the “Score” given to each reaction type.
- We therefore need data showing the content ID, category, content type, reaction type, and reaction score.
- So, to figure out popularity, we’ll have to add up which content categories have the largest score.

### Data cleaning
Before we start working of on the datasets its important to have a clean data for analysis
Open the three data sets and Clean the data by:
- removing rows that have values which are missing,
- changing the data type of some values within a column,
- and removing columns which are not relevant to this task or to the business question that needs to be analysed.
- If a column may not be useful in analysis,its worth removing it.

### Data modelling
Now its time to figure out the top 5 categories. To complete the data modelling, following steps are performed:

1. Created a final data set by merging three tables together by using "VLOOKUP"
2. Figured out the Top 5 performing categories by adding up the total scores for each categories using "SUMIF"

### Data Visualisation and Insights
Now its time to bring the data analysis to life by creating colourful visualisation and useful insights for the client.
Please refer to the excel sheet and ppt for the visuals and insights that has been provided to the client.


 

