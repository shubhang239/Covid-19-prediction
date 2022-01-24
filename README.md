<h2>Covid-19-prediction</h2>
<div>
  <p>This was an end semester project for my subject <b>SE -327 Method in Data Analytics.</b> The aim of the project was primarily data analysis and visualization of COVID-19 cases specifically focussing on India. At a later stage however i decided to add some prediction component using the Time Series Modelling techniques. As a novice in this field there is a lot that can be improved as far as predictions are concerned. If anybody decides to work upon this further to better this work you are most welcome. Do reach out to me on my
  <a href="mailto:fighterengineer31@gmail.com" target = "_blank">Gmail</a></p>
</div>

## Introduction
The WHO declared COVID-19 as a pandemic in February 2020. What started in Wuhan in China in a matter of 30 days spread to more than half of the countries. As the entire world
grappled with this new virus, wearing masks and social distancing was the only way out. Almost a year later a vaccines were in the last stage of development and cases seemed to decline we were hit by the 2nd wave. This unpredictability in infections and waves in which it is coming points towards the need to be able to forecast the cases
in order to be better prepared. Using Machine Learning techniques some amount of prediction can be made to understand the trends.

## Dataset Collection
The dataset has been downloaded from 

## Data Pre-processing
<div>
  <li><b>Feature Selection</b> The dataset which we took was huge with many attributes. Keeping only relevant columns out of the large database from our analysis point of view was the first step before starting the analysis.The file in csv format, was first studied, verified and cleaned in Excel and then loaded into Python for analysis.</li>
  <li><b>Data Structuring</b> The data sourced directly contained everything bundled together in a single data frame hence structuring the data was done as required for the relevant analysis.</li>
  <li><b>Data Cleaning</b> The data first had to be cleaned by removing the Null and missing values. There were a lot of missing values which means that for a particular date, the data for covid cases was not updated. Datatype also had to be changed such as the time was in a string format which was converted to datetime.</li>
  <li><b>Outlier Detection and Data Scaling</b> The dataset also contained cumulative or total values of confirmed cases/ deaths etc in between the rows. These are outliers and they had to be made into a separate data frame. values of total cases and deaths etc number in millions, hence for the purpose of understanding, comparing and plotting we had to scale them by a factor of E-6. Further for calculating the percentages we had to normalize the values.</li>
</div>

## EXPLORATORY ANALYSIS
Exploratory Data Analysis was carried out after the data was cleaned and structured. EDA helps in getting familiar with the data and understanding basic trends and summary
statistics. We divided our EDA approach into three parts. The first part was an analysis of the states followed by the entire country and finally for the cumulative of all countries. The trends of rise in cases, active cases and deaths were analyzed and compared across the states.
