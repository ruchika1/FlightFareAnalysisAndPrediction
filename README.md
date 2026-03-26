### Project Title
Flight prices exploratory data Analysis
**Author**
Ruchika Rawat

#### Executive summary
In this section I will explore the Flights pricing details and analyse what features of the chosen data set influence the price. I will also present correlation of various components to each other as well as to the target feature - flight price

#### Rationale
Why should anyone care about this question?
Flight pricing is very competitive, with a large number of carriers in each sector.
This kind of analysis could be helpful in finding opportunities to improve revenue and reduce loss of business due to high prices.

#### Research Question
What are you trying to answer?
What is the correct price for a flight from a given source to destination?

#### Data Sources
What data will you use to answer you question?
I found free dataset on Kaggle which is very popular - https://www.kaggle.com/datasets/nikhilmittal/flight-fare-prediction-mh

#### Methodology
What methods are you using to answer the question?
For first step tackled in this notebook is exploratory data analysis -
1. Drop all rows with null data
2. Drop price column from data and store in a target dataframe Y
3. Split data into train, test subset
4. utilize various plotting and summarization methods in seaborn and matlab to develop an understanding of data
5. convert Date_of_Journey from string to datetime
6. Compute duration of flight in hours and minutes
7. Convert stops from string to int


#### Results
What did your research find?
I plotted various features and concluded as follows
1. Using a barplot of flights by airlines - majority data is for jet blue
2. Using a barplot of flights by month - all of the data is over a span of just 4 months
3. Using a distribution of flight prices - majority of flights have price <10000
4. Using a correlation matrix of various features - it appears that the top two contributing factor to price are number of stops and duraiton
5. Using a barplot of flights by routes - the most common route found in this data is Delhi - cochin

#### Next steps
What suggestions do you have for next steps?
Next steps are to develop a model that can take a source and destination input and predict a price.

#### Outline of project

- [Exploratory Data Analysis](https://github.com/ruchika1/FlightFareAnalysisAndPrediction/blob/main/FlightsData.ipynb)



##### Contact and Further Information
