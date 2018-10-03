# Board Games and Video Games
## Understanding Different Languages

The goal of this project was to better understand the board gaming and video gaming communities by determining the differences in their word choice. Using the Reddit API, I scraped over 5,000 posts from the board game and video game subreddits. I stemmed and applied a TFIDF vectorizer to the posts. From there, I optimized the hyperparameters of different classifiers. I chose a logistic regression due to strong predicatability and interpretability. It was able to determine subreddits with 98% accuracy. Using it, I could determine which words were the best predictors of each subreddit.

How to explore this repo:
- Reddit scraping has the full project from scraping through modeling
- Extension has exploration of positive and negative rating indicators in the two communities (ongoing)
- Presentation is a recorded video going through the process and results of the project
