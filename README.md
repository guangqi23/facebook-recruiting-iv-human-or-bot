# facebook-recruiting-iv-human-or-bot

# Introduction

In this Jupyter notebook, I present my approach to the recent Kaggle competition, [Facebook Recruiting IV: Human or Robot?](https://www.kaggle.com/c/facebook-recruiting-iv-human-or-bot). The main idea was to treat the modeling problem as somewhat of a text classification problem by sorting the bid data for each bidder in chronological order and using this sorted bid data as a text-based "fingerprint" of the bidder's activities. In addition to this, I computed some numerical features for the time differences between bids and the unique counts of the different entries. The final model ended up being a bag of 15 XGBoost models on a sparse matrix of tfidf-vectorized text features concatenated with scaled numerical features.
