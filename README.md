
#### About the Project

In this project I downloaded data manually and programmatically from URL using Request library. Using the tweet IDs in the WeRateDogs Twitter archive, queried the Twitter API for each tweet's JSON data using Python's Tweepy library and stored each tweet's entire set of JSON data in a file called tweet_json.txt file. Wrote each tweet's JSON data into its own line. Then read this .txt file line by line and converted into a DataFrame using Pandas library. Gathered all data in variety of formats, accessed its quality and tidiness then cleaned it. Visualized data to find trend on them.

#### Files Related to this Project 
- WeRateDogs_Data_Wrangling_Python.ipynb <- This is the main file that has the whole analysis of data.
- Wrangle_act.pdf <- This file contains the summary of data after analysis is done
- Wrangle_report.pdf <- This file contains the process of gathering, accessing and cleaning data. It also contains the challenges I facede during ETL.
- image_predictions.tsv <- Image prediction data downloaded programatically using requests library.
- tweet_json.txt <- text data downloaded from tweeter using tweepy library.
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
