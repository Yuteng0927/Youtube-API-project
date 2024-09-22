**[authors](#authors) | [summary](#summary) | [limitation ](#limitation ) | [usage](#usage) | [visualization](#visualization) **



# Project :  YouTube API Project*

## Authors
•	Yuteng Zhang
•	Dipti Sontakke
•	Alejandro Gutierrez
•	Patrick Brennan
•	Daniel King-Alan


## Summary 
This project observed the YouTube ‘s Videos category, counts, likes and comments based per country and its relation to each other. This project answers the question
Our analysis focuses on answering below questions: 
•	Is there a significant difference in the average like count of the top 50 videos within each designated region within YouTube? 
•	Ha: Average like count will be significantly different between the regions 
•	H0: There is no difference between the average like count by region 
•	Is there a significant difference in the average like count of the top 50 videos of each designated category within YouTube? 
•	Ha: Average like count will be significantly different between the categories 
•	H0: There is no difference between the average like count by category 
•	Additional Correlations: 
What is the average percent of videos liked by the number of views they have received? 

## Limitation  
Could only pull 50 videos per country. Also the API which could pull the Category of videos was under maintenance  by YouTube so we had to come up with list of 20 category’s (Google search) and use them in project. Also retrieved files per day changes the amount of record. So we have retrieved 5000 records for one and did the analysis.

- How this project works :** 
Project is built to call the YouTube API’s dataset related to Video . Due to large size,  dataset is saved in CSV file for further analysis(5000 records). Python matplotlib, bar graph, pie charts are used to analyzed the data and specify the correlation in between videos, categories, likes, views and counts. Various methods such a correlation, aggregation, t-test, comparison , ANOVA tests are used to do further analysis of data.

## Usage
- Python 
- YouTube API
- GitHub
- Jupyter Notebook
- CSV Files

## Visualization
As part of Data Visualization, Bar graphs , Pie Charts, Box Plots are used to display correlation and linear regression of data. P-value and t-test , ANOVA  test, linear regression tests are also calculated to show the relation between data and its hypothesis acceptance.

![image](https://user-images.githubusercontent.com/112952607/199349475-72270c04-68a7-4e91-afd6-8f12c7cae788.png)


![image](https://user-images.githubusercontent.com/112952607/199349492-fa91d4a3-e602-4ce6-82b1-e5a94b78986f.png)


![image](https://user-images.githubusercontent.com/112952607/199349506-a4139a2a-fed6-447b-8752-8b0463c83298.png)


![image](https://user-images.githubusercontent.com/112952607/199349525-c409162e-723f-43b7-a1f1-c8a0cd42b3ef.png)


![image](https://user-images.githubusercontent.com/112952607/199349545-c0935737-8dd7-48e0-97c0-69192c0dce1f.png)


![image](https://user-images.githubusercontent.com/112952607/199349565-3c1ceb17-e3e3-4b32-87c3-64da8044f16e.png)


![image](https://user-images.githubusercontent.com/112952607/199349582-ae9bc4ad-424f-4042-8dad-7867532847c1.png)

**References :** 
YouTube API -  https://developers.google.com/youtube/v3 
Python - https://pandas.pydata.org/ 
GitHub - https://github.com/PatttyCakess/Youtube-API-project 

