# Reddit NLP Classification

### Executive Summary

In this project, I will explore two Reddit Subreddits, [r/Futurology](https://www.reddit.com/r/Futurology), and [r/AskScience](https://www.reddit.com/r/askscience).

Utilizing natural language processing, I will build a Logistic Regression, Multinomial Naive Bayes, and Random Forest model to predict the subreddit classification of every text post.

![Future](https://i.imgur.com/W7kPDOM.png)
![Ask Science](https://i.imgur.com/ggJ7G0O.png)

#### About the Subreddits

__Futurology__ is a community of 14.6 Million users that exists to speculate on technology and scientific discoveries that will have an impact on humanity's future development. 

__AskScience__ is a community of 19.1 Million inquisitive users (and scientists) which exists to ask and answer questions related to scientific discoveries, or even just general science-related questions.

* * *

### Problem Statement

Naturaal Language Processing is a part of life at this point. We don't even think about asking Siri or Alexa for something -- it's as intuitive as Google searching was just five years ago. We are living in a world in which we regularly interact with and rely on computer-generated information. 

Being able to properly identify where user inputs belong? This will be critical for further development of NLP.

* * *

### Data

| Predictive Variable | Data type | Description |
  ------------------- | --------- | ----------- 
| sentiment | float | Average score (from -1 to 1) of positive vs. negative words per post |
| word_count | int | Number of words in a post |
| title_selftext | object(str) | Combining 'title' and 'selftext' of every post|

* * *

### Frequently Used Words/Bigrams:

![Words](https://i.imgur.com/1NrOItu.png)

![Bigrams](https://i.imgur.com/njrkKRG.png)
