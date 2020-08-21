# covid_analysis
Analysis of cumulative progression of COVID-19 in various countries

# Step 1: Finding Data
i) Datasets on time-series of COVID-19 confirmed cases, deaths and recoveries (updated till August 2, 2020) - https://data.humdata.org/dataset/novel-coronavirus-2019-ncov-cases?force_layout=desktop#        
ii) Dataset on World Happiness Scores 1 - https://www.kaggle.com/unsdsn/world-happiness       
iii) Dataset on World Happiness Scores 2 - https://www.kaggle.com/unsdsn/world-happiness?select=2019.csv

# Step 2: Data Cleaning 
i) Removed unnecessary and/or irrelevant rows and columns. This provides for results with better accuracy and consistency.                
ii) Managed columns(names and data) such that they are easy to interact with.

# Step 3: Calculations
i) Computed 'maximum increase rate' of confirmed cases for all countries from their cumulative values.                       
ii) 'Joined' the values with the data from World Happiness Scores.                                 
iii) Correlated the values of the two datasets to see if the factors of happiness affect the increase rates of COVID-19 in the countries, and how they are related.

# Step 4: Visualisation
i) Scatterplots
and                                                
ii) Regression plots, to show generalised relations of the above calculations.
