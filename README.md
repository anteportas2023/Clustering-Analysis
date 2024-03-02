# Clustering-Analysis

### Problem formulation

- In this example, we want to create a Segmentation with customers who behave the same

- We want to investigate what are the common traits / behaviours in each Segment / Cluster

- We want to deploy our results in Power BI for the business to use

- We want to automate all this process for future data

### Code and Tools Used

**Anaconda**: JupiterLab

**Packages**: pandas, numpy, sklearn, matplotlib, seaborn

PowerBI

### Data Preprocessing

I needed to clean it up so that it was usable for our model. I made the following changes and created the following variables:

- Removed 5 rows with NaN values in the column Total_Household_Income
- Divided variables into Categorical and Numerical

### Feature Engineering

- Creating a distance metric
- Convert the Categorical variables into Numeric Representation


### Model Building

- K-means Clustering
- Running Principal Component Analysis (PCA) to Visualize & improve results
- Another way of "Improving" results Could be to Clean/Combine Variables
- Export data in a csv

### Deploy results in Power BI for the business to use

- Creating the front end PowerBI Dashboard
- Creating Insights from Clusters
- Creating NPS analytics per Cluster

### Insights:

**Cluster 1 Traits**

- Mostly people with age being 50+
- Mostly Married with Children
- Household Income ranges from 25k to 100k
- Attend Events 3 to 4 times a year
- Don't spend too much time on Social Media (< 1 hour)
- Willing to travel 4 - 6 hours
- Kids Playgrounds is their favourite attraction
- Very satisfied with last event

**Cluster 2 Traits**

- People who don't have kids - mostly single
- Earn between 20k to 50k
- Attend events mostly once or twice a year
- Spend a lot of time in Social Media; half a day +
- Willing to travel 1 to 2 hours
- Love adrenaline rush activities
- Not bothered with food/coffee/bars/toilet areas
- Somewhat satisfied with last event
- Somewhat likely to recommend it to others
- Event was not value for money

**Cluster 3 Traits**

- Mostly people with age range between 26 to 50
- Married people who have kids or living with their partners (2+)
- Earn between 50k to 150k
- Attend events 3 to 4 times a year
- Spend mostly 1 to 2 hours in social media
- Mostly willing to travel 4 to 6 hours
- Like a bit of everything in the attractions
- Very likely to recommend their last event
- Very "general" group of people; maybe willing to try new things

**Cluster 4 Traits**

- People who single, separated, divorced or widowed
- Household income ranges between 50k to 100k or less than 20k
- Attend a lot of events per year; 5 plus
- Spend half a day in social media
- Willing to travel up to 6 hours and they love adrenaline rush activities
- Not bothered with food/bars/coffee/toilet areas
- Mostly satisfied with their last event and willing to recommend
- They do not think the last event was value for money

**Cluster 5 Traits**

- Mostly people between 40 to 60 age
- Married with children
- High earners; making 100k +
- Attend events 3 times a year
- Do not spend much time on social media; 1 hour or less
- Willing to travel 4-6 hours for the event
- Not adrenaline people
- Food/Coffee/bars/toilets are very importance
- Kids playgrounds are essential
- Very satisfied with last event BUT* Unlikely to recommend (dummy data)
- Last event was value for money

