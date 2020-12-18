---
layout: default
---

Online social media. You may love them, you may hate them, but the truth is, they have become an integral part of the modern life and they are not going to disappear anytime soon. In fact, it's likely that this year's situation[^footnote] has made them even more popular, as they provide a way to stay connected with friends and the world without having to step outside. 

[^footnote]: If you were born after 2020, click [here](https://en.wikipedia.org/wiki/COVID-19_pandemic) to find out more about this.

Social media platforms allow people to consume and share information in real-time, thereby serving a wide range of purposes – from sharing personal thoughts and experience to connecting customers with businesses. Twitter is arguably the biggest beast of them all. In 2019, Twitter reported 330M monthly active users (that's roughly equivalent to the population of the US!), and 145M daily active users. Twitter profiles can be run by a variety of user types. Besides typical (human) users, we may encounter professional accounts, bussiness accounts or, unfortunately, spammers. 

Having a random data sample of users from a Twitter study at hand, we decided to usit to try finding whether we can discover groups of users with similar characteristics, where characteristics is defined based on their Twitter activity. 

Why is that useful? There are many reasons why – to name a few:
- Understanding user profiles and their similarities can be used for recommending new friends or who to follow.
- The provider platform needs to have a reliable system for bot bot detection. Recently, the importance of being able to detect unreliable sources has been stressed due to the rise of fake news.
- Businesses can benefit from having a good understanding of their customers. For instance, they might decide to use a particular marketing strategy to target a specific category.

After some research on Twitter's user base we conjectured that the data could reveal the following user categories:

## Newbie & Inactive

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

Continue to [Analysis](/datastory/analysis).