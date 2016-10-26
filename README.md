# Multilingual-Search-System-for-Tweets
Apache Solr

Collecting Tweets

Used twitter4J(Twitter4J is an unofficial Java library for the Twitter API) to crawl through twitter API.
An access token is needed to connect to twitter API) to collect the tweets.
A java program was written where a object of class twitter was created which has a search method to which a query was passed a parameter.
The output were number of tweets where each tweet was stored as a JSON object, thus creating an array of JSON objects stored in a JSON File.

The Tweets were Tokenized and Indexed using Apache Solr

Implemented the UI using Bootstrap to display query results based on ranking scheme selected by user.
