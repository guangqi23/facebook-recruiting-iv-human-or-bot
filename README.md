# facebook-recruiting-iv-human-or-bot

# Introduction
In this Jupyter notebook, I present my approach to the recent Kaggle competition, [Facebook Recruiting IV: Human or Robot?](https://www.kaggle.com/c/facebook-recruiting-iv-human-or-bot). 

# Problem
For this competition, we will be chasing down robots for an online auction site. Human bidders on the site are becoming increasingly frustrated with their inability to win auctions vs their software-controlled counterparts. Goal of this competition is to identify online auction bids that are placed by bots, helping the site owners to easily flag these users for removal from their site to prevent unfair auction activity.

# Libaries 
For the most part, I used Python standard libraries and the scientific Python libraries available in the Anaconda distribution (pandas, scikit-learn, scipy and numpy). 
For the libaries, I used the standard libaries in Python ( pandas , numpy , scikit-learn ).


<pre>
    <code>
    ```python
    import numpy as np
    import pandas as  pd
    from sklearn.model_selection import train_test_split
    from sklearn.ensemble import RandomForestClassifier
    import xgboost as xgb
    from catboost import CatBoostClassifier      
    from sklearn.ensemble import GradientBoostingClassifier
    from sklearn.model_selection import KFold
    import statistics
    import sklearn.metrics as metrics
    from sklearn.metrics import accuracy_score
    from sklearn.metrics import roc_curve,auc
    from sklearn.metrics import roc_auc_score
    ```
    </code>
</pre>
