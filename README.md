# YouTube_comment_sentiment_analysis

# Motivation
YouTube, the world’s second-largest search engine, is a massive hub of diverse content — from entertainment and education to lifestyle and beyond. One of the most valuable yet often overlooked parts of any video is its comment section. It reflects the audience’s sentiments, provides feedback for creators, and serves as a space for viewer interaction.

However, there's a growing challenge: the rising tide of spam comments. These not only clutter the conversation but also pose a serious threat, being a common source of scams and misinformation. For content creators, this makes it increasingly difficult to analyze genuine feedback and understand their audience’s needs.

Moreover, with large channels generating thousands of comments per video, manually analyzing them becomes nearly impossible. This is where automated comment analysis becomes essential — both for creators and viewers. While creators can use it to adapt their content and improve engagement, viewers benefit too: by skimming through top comments, they can quickly gauge the value and relevance of a video, especially in an age of clickbait titles and misleading thumbnails.

Additionally, since YouTube removed the public dislike counter, analyzing comment sentiment can serve as an alternative metric for audience reception — offering a clearer picture of whether a video is well-received or not.

# Problem Statement
Extract all the comments of a YouTube video and predict the Spam Comments using the Classification model trained on the spam comments dataset. Then perform a sentimental analysis and generate a Word Cloud to get the hot topics people are talking about after eliminating the spam comments and finding out the number of negative and positive comments to decide whether the content is liked by viewers or not.

# Algorithms & Tools used
- NLTK (Natural Language Toolkit)
- Sklearn, NumPy, Matplotlib, Pandas
- SVM (Support Vector Machine)
- Logistic Regression
- Text Analytics
- Word Cloud
- NLP (Natural Language Processing)
- Google API Client

# Dataset Used
- https://www.youtube.com/watch?v=kX3nB4PpJko for “comments_dataset.csv” extracted using API.

- https://www.kaggle.com/datasets/lakshmi25npathi/images for “Youtube01-Psy.csv”.
