This project creates and updates a Google Sheet with relevant tweets and a basic sentiment analysis of this tweet.

**The problem**

I was monitoring a few companies in the context of a larger project and needed to get an update of their activity and what the public thought about them. While I was reading the news and checking sometimes social media, I needed to find a more efficient way to see and analysis what was going on.

**The solution**

I created several pieces of code to analysis online newspapers and social media. This particular code here scraps Twitter and returns structured information about the latest tweets.

**The risks**

I couldn't scrap tweets that were older than 2 weeks
the keywords I used were basics and therefore, combined with the noise on the social platform, I could not trust 100% the results

**The tools**

I used several libraries:

(Aylien)[aylien.com] They are a company specialised in NLP product. They provide an API with a limit of calls per day. Their NLP library gave me a more precise results than the TwitterSearch Library as well as a percentage of confidence.

Google Sheet
I used the Google Sheet API because I am a big fan of observing my results directly in an Excel when I can to give me a clear results and also to share them quickly with others. This API set up has changed a little bit since I have written this code but the concept is the same. More information can be found (here)[https://developers.google.com/sheets/api/]

TwitterSearch There is a lot of API wrapper for Twitte out there but I like this one in particular because of the clarity of the documentation and the functions provided. (This library)[https://pypi.org/project/TwitterSearch/] has been created by the Technical University of Munich.
