# Multilingual-Search-System-for-Tweets
Apache Solr

Collecting Tweets:- Used twitter4J(Twitter4J is an unofficial Java library for the Twitter API) to crawl through twitter API.
An access token is needed to connect to twitter API) to collect the tweets.
A java program(collect-tweets-java-class.txt) was written where a object of class twitter was created which has a search method to which a query was passed a parameter.
The output were number of tweets where each tweet was stored as a JSON object, thus creating an array of JSON objects stored in a JSON File.

The Tweets were Tokenized and Indexed using Apache Solr(schema.xml file was used in solr)

Various IR models were evaluated as well as language detection, query translation and expansion techniques were used in performance analysis.(check report)

Implemented the UI using Bootstrap(searchengine_ui.html) to display query results based on ranking scheme selected by user.
