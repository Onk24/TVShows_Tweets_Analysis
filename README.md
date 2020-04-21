# TVShows_Tweets_Analysis

**Processing Tweets & Analyzing Sentiments for Business Insights**: Tweets from TV Shows are analyzed to understand the sentiments. The workflow is as follows: <br>
- Data Extraction: Python library GetOldTweets3
- Data Storage: MySQL database on Google Cloud
- Data Processing and Basic Analysis: PySpark SQL and PySpark DataFrame
- Advanced Analysis: Python libraries like Seaborn, NLTK, TextBlob

The data is restricte to 14,000 records for 2 TV shows over 7 days.  <br>
Data Processing and Basic Analysis is done using **SparkSQL and PySpark DataFrame** methods
Following metrics are identified from the analysis: <br>
Basic Metrics <br>
 - Total Users: 13,018
 - Total Tweets: 14,000
 - Total Days: 7 days <br>
 
Advanced Metrics (Popularity Metrics) <br>
- Average likes per Tweet <br>
Money Heist: 4.3 <br>
Tiger King: 7.7
- Average Retweets per Tweet  <br>
Money Heist: 0.7 <br>
Tiger King: 0.87 <br>

Furthermore we do Advanced Analysis to identify positive, negative or neutral sentiment for every tweet using **NLTK and TextBlob** library <br>

 
