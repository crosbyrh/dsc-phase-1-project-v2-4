# Overview


The purpose of this project is to help Microsoft find the most effective way to allocate its capital while starting a new movie studio.  
Movies can be extremly expensive to create, so choosing the right type of movie to create (budget size, genre, critical expectation), can potentially have large affects on financial success of the enterprise.   
The Jupyter Notebook in the repository shows and explains how I went about brining in appropriate data sets from public sources and processing that data to come to strategic conclusions/suggestions. 
The repository contains the data locations and also the notebook with the data analysis.  

# Business Understanding

Microsoft is a 1.77T technology company that seeks a new business line that will be net financially beneficial for the company.  

# Stakeholder and key business questions

Microsoft will be the investort in the new project and these are the key business questions we want to address:

Large budget or small budget films?
Specific genre?
Popularity? 



# Data Understanding and Analysis

For this project we analyzed a variaty of data formats csv and sql.  We moved the data into dataframes to more easily use pandas in python.  We mainly wanted to find relationships between different factors and how they affect the success defined as net profit of the movie.  

# Source of data
We used and analyzed data from IMDB, TheMovieDB, and The Numbers. 
Net Return = worldwide gross – production budget
We calculated percentage gain as net return divided by production budge


# Three Visualizations

### production budget vs. net returns
<img width="388" alt="image" src="https://user-images.githubusercontent.com/109488147/193263307-270bae88-5381-43f0-9cd7-adebc3759ea8.png">

### genre vs. net returns
<img width="851" alt="image" src="https://user-images.githubusercontent.com/109488147/193263420-4b346e62-8ccd-46a9-9ca5-e90e13673f16.png">

### Popularity vs. net returns
<img width="507" alt="image" src="https://user-images.githubusercontent.com/109488147/193263517-c203234e-601b-44b3-8f0b-fdb1403b4672.png">


# Conlusion 
The analysis came up with these three conclusions:

Pursue big budget films- we saw that looking at net returns didn't show a strong relationship.  
Pursue Sci-fi, Animation and Adventure genres- we saw which genres had the highest net returns
Popularity leads to higher net returns- we saw a positive relationship between popularity and returns.  




Here is a link to the notebook http://localhost:8888/notebooks/student.ipynb

Here is a link to the presentatin http://localhost:8888/files/Presentation.pdf









