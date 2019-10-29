This is the PYTHR-august-2019 final project based on Russian Troll Tweets. This project will not have the entire public dataset, only a subset. Below is additional details of the Github page - https://github.com/fivethirtyeight/russian-troll-tweets/


# russian-troll-tweets-Final-Project
This data was used in the FiveThirtyEight story Why We’re Sharing 3 Million Russian Troll Tweets.  This directory contains data on nearly 3 million tweets sent from Twitter handles connected to the Internet Research Agency, a Russian "troll factory" and a defendant in an indictment filed by the Justice Department in February 2018, as part of special counsel Robert Mueller's Russia investigation. The tweets in this database were sent between February 2012 and May 2018, with the vast majority posted from 2015 through 2017.  FiveThirtyEight obtained the data from Clemson University researchers Darren Linvill, an associate professor of communication, and Patrick Warren, an associate professor of economics, on July 25, 2018. They gathered the data using custom searches on a tool called Social Studio, owned by Salesforce and contracted for use by Clemson's Social Media Listening Center.  The basis for the Twitter handles included in this data are the November 2017 and June 2018 lists of Internet Research Agency-connected handles that Twitter provided to Congress. This data set contains every tweet sent from each of the 2,752 handles on the November 2017 list since May 10, 2015. For the 946 handles newly added on the June 2018 list, this data contains every tweet since June 19, 2015. (For certain handles, the data extends even earlier than these ranges. Some of the listed handles did not tweet during these ranges.) The researchers believe that this includes the overwhelming majority of these handles’ activity. The researchers also removed 19 handles that remained on the June 2018 list but that they deemed very unlikely to be IRA trolls.  In total, the nine CSV files include 2,973,371 tweets from 2,848 Twitter handles. Also, as always, caveat emptor -- in this case, tweet-reader beware: In addition to their own content, some of the tweets contain active links, which may lead to adult content or worse.  The Clemson researchers used this data in a working paper, Troll Factories: The Internet Research Agency and State-Sponsored Agenda Building, which is currently under review at an academic journal. The authors’ analysis in this paper was done on the data file provided here, limiting the date window to June 19, 2015, to Dec. 31, 2017.

The files have the following columns:

|Header |	Definition |
| ----- | ---------- |
|external_author_id	| An author account ID from Twitter|
|author	|The handle sending the tweet|
|content	|The text of the tweet|
|region	|A region classification, as determined by Social Studio|
|language|	The language of the |
|publish_date	|The date and time the tweet was sent|
|harvested_date|	The date and time the tweet was collected by Social Studio|
|following|	The number of accounts the handle was following at the time of the tweet|
|followers|	The number of followers the handle had at the time of the tweet|
|updates|	The number of “update actions” on the account that authored the tweet, including tweets, retweets and likes|
|post_type|	Indicates if the tweet was a retweet or a quote-tweet|
|account_type	|Specific account theme, as coded by Linvill and Warren|
|retweet|	A binary indicator of whether or not the tweet is a retweet|
|account_category|	General account theme, as coded by Linvill and Warren|
|new_june_2018|	A binary indicator of whether the handle was newly listed in June 2018|
|alt_external_id	|Reconstruction of author account ID from Twitter, derived from article_url variable and the first list provided to Congress|
|tweet_id|	Unique id assigned by twitter to each status update, derived from article_url|
|article_url	|Link to original tweet. Now redirects to "Account Suspended" page|
|tco1_step1	|First redirect for the first http(s)://t.co/ link in a tweet, if it exists|
|tco2_step1	|First redirect for the second http(s)://t.co/ link in a tweet, if it exists|
|tco3_step1	|First redirect for the third http(s)://t.co/ link in a tweet, if it exists|
