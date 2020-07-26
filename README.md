# Tweet-Analysis
To come up with a solution that can be utilized by users to correctly categorize tweets and counter them for better customer experience.
#### Problem Description

* Customer support in channels like Twitter and Facebook has became a challenge because having a negative reviews or comments can largely impact the sales, profitability and customer experience.
* The main challenge in this line of research is collecting quality data.

#### Analytics Objective

*  To come up with a solution that can be utilized by users to correctly categorize tweets and counter them for better customer experience.
* Sentiment analysis of the each tweet.
* To identify the top customer support companies.

#### Dataset Description

The dataset is a csv, where each row is a tweet. Each conversation includes at least one customer request and one company reply.

* tweet_id:	A unique, anonymized ID for the Tweet. Referenced by response_tweet_id and in_response_to_tweet_id.
* author_id: A unique, anonymized user ID. In the dataset have been replaced with their associated anonymized user ID.
* inbound: Whether the tweet is "inbound" to a company doing customer support on Twitter. This feature is useful when re-organizing data for training conversational models.
* created_at: Date and time when the tweet was sent.
* text: Tweet content.
* response_tweet_id: IDs of tweets that are responses to this tweet.
* in_response_to_tweet_id: IDs of the tweet is in response to, if any.

#### Experiment

* To build a unsupervised machine learning model to correctly cluster the user tweets.
