---
layout: default
---

Online social media. You may love them, you may hate them, but the truth is, they have become an integral part of the modern life and they are not going to disappear anytime soon. In fact, it's likely that the social distancing measures imposed this year due to the pandemic has made them even more popular, as they provide a way to stay connected with friends and the world without having to step outside. 

Twitter is arguably the biggest beast of them all. In 2019, Twitter reported 330M monthly active users (that's roughly equivalent to the population of the US!), and 145M daily active users. ***Develop***

Having a random data sample of users from a Twitter study at hand, we decided to usit to try finding whether we can discover groups of users with similar characteristics, where characteristics is defined based on their Twitter activity. More precisely, we looked at the following properties: ***list of features used for clustering and their description***

After some research on Twitter's user base we conjectured that the data could reveal the following user categories:

## Newbie / Inactive

- Joined because of peer pressure
- Has not (yet) posted a single tweet
- Follows only a few other users
- Has very few followees 
- No mentions (yet?)

## Incognito

- Active but rarely tweets or retweets
- Follows many users
- Not followed by many
- Not many mentions



## Retweeter

- Similar to incognito
- Rarely tweets but reweets a lot



## Community builder

- Fairly balanced number of followers and number of following users
- Retweets and mentions posts from their community
- Number of tweets may vary



## Celebrity, Influencer & Media, Businesses

- Tweets a lot
- Mentioned a lot
- Retweeted a lot
- Has much more followers than the number of users they follow
- Uses hashtags, URLs 



## Bot & Spammer

- Post many tweets (often duplicates & containing URLs)
- Might follow many users but are not followed much themselves
- No mentions or reweets



There are of course many profiles that don't fit any of the above descriptions, however we estimate that these categories should account for at least 80% of Twitter's user base. 

