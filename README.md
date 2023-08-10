# TwitterDataWithNeo4j

In this project we use data extracted from the Twitter API, save them into a local MongoDB instance and then import analyze them using Neo4j.

Please check out the corresponding [Medium Article](https://medium.com/@thdiamant/exploring-twitter-data-with-neo4j-and-python-f97ab427db56) for more details.

Namely, the following queries were answered:

1. Get the total number of tweets.

2. Get the total number of hastags (case insensitive).

3. Get the 20 most popular URLs in descending order.

4. Get the followers count of each user.

5. Get the number of tweets & retweets per hour.

6. Get the user with the most replies.

7. Get the top-20 hashtags that co-occur with the hashtag that has been used the most.

8. Get the most "important" user in the dataset (user Graph algorithms: Pagerangk, Betweenness centrality, etc). You will apply these algorithms in the mention netwwork (which includes retweets).

9. For the 5th most important user, get the list of hashtags and URLs that have been posted (if no hashtags or URLs - check another user, e.g. 6th, 7th, etc...).

10. Get the user communities that have been created based on the users' interactions and visualize them (Louvain algorithm). (G P)

11. Get the top-10 users who posted the most tweets during the year 2022. In order to count a tweet, it should contain at least one of the top-5 mostly used hashtags of all time.

12. Get the users which have minimum average tweets per day bigger than the average number of tweets of a user per day. Only users with more that 2 tweets per day will be used in order to calculate the average number of tweets per day.

