
#### About the Project

This project is a part of Data Analyst Nanodegree. Data Wrangling is the main task in this project.
I downloaded data manually and programmatically from URL using Request library. Using the tweet IDs in the WeRateDogs Twitter archive, queried the Twitter API for each tweet's JSON data using Python's Tweepy library and stored each tweet's entire set of JSON data in a file called tweet_json.txt file. Wrote each tweet's JSON data into its own line. Then read this .txt file line by line and converted into a DataFrame using Pandas library. Gathered all data in variety of formats, assessed its quality and tidiness then cleaned it. Visualized data to find trend on them.

#### Files Related to this Project

- WeRateDogs_Data_Wrangling_Python.ipynb <- This is the main file that has the whole analysis of data. Code written for all gathering, assessing, cleaning, and visualization process.
- Wrangle_act.pdf <- This file contains the summary of data analysis. I have attached plots, those are very informative to explain relation between retweet count and favorite counts with rating.
- Wrangle_report.pdf <- This file contains the process of gathering, accessing and cleaning data. It also contains the challenges I faced during ETL.
- image_predictions.tsv <- Image prediction data downloaded programmatically using requests library.
- tweet_json.txt <- Text data downloaded from tweeter using tweepy library.
- twitter_archive_master.csv <- Final data set after cleaning/merging/transferring.

#### Python Libraries used
- Pandas
- Numpy
- json
- requests
- tweepy
- wordcloud
- warnings
- matplotlib
- seaborn
