# TVShows_Tweets_Analysis

**Processing Tweets & Analyzing Sentiments for Business Insights**
Tweets from TV Shows are analyzed to understand the sentiments. The workflow is as follows: <br>
- Data Extraction: Python library GetOldTweets3
- Data Storage: MySQL database on Google Cloud
- Data Processing and Basic Analysis: PySpark SQL and PySpark DataFrame
- Advanced Analysis: Python libraries like Seaborn, NLTK, TextBlob

The data is restricte to 14,000 records for 2 TV shows over 7 days. Following metrics are identified from the analysis:
- Basic Metrics
 - Total Users: 13,018
 - Total Tweets: 14,000
 - Total Days: 7 days
- Advanced Metrics (Popularity Metrics)
 - Average likes per Tweet 
 - Money Heist: 4.3
 - Tiger King: 7.7
 - Average Retweets per Tweet 
 - Money Heist: 0.7
 - Tiger King: 0.87


The first 3 questions are answered in the **Inferential Analysis** section while the last question is answered in the **Predictive Modeling** section. 
 
