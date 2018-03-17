# Twitter-Web-Scraper-Python
Collect data from Twitter API and store it in CSV.
twitterScrapper.py is a python script containing code to collect data from Twitter account the data collected is mentioned below.

# Twitter Account details fetched -
Twitter Account Name, Twitter total tweets of account, total followers and following count, Twitter total Page likes, twitter total lists of account, Data Collection time.

# Tweet details fetched -
Twitter Tweet URL, Tweet Creation Time, total Tweet likes, if tweet is retweeted or not?, who has retweeted the tweet (retweeted from),  total Tweets retweets, Tweet Text, Total Tweets tagged picture count, total tweets tagged video count, total hashtags in the tweet, tweet Hashtag texts, tweets total links in post and 3 separate links in separate cells.

# How to Run?
1. pip install tweepy
2. Create a twitter developer account and create an application to get access to API and their secret keys.
3. In the file edit the consumer_key, consumer_secret, access_key, access_secret keys with your application keys.
4. Change page_id list with list of screen_names i.e. twitter accounts you need to have data for (you can put multiple names as well).
5. In collect_tweet_data function change the count=50 to number of tweets you want to collect from any account.
6. Run the script without any runtime arguments.
7. The CSV (twitterScrapper.csv) will be stored in the path where the script is stored.
