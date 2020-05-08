# Hybrid Recommender System

Project builds a hybrid recommender system for books combining multiple individual recommenders with high accuracy. 

Dataset : https://www.kaggle.com/zygmunt/goodbooks-10k  
Evaluation metric : **R2-score**

### Objective
To see if hybrid recommender has improved performance over individual recommenders.


### Recommender System
A recommender system tries to predict the rating a user would give to an item, and based on those ratings, recommends relevant items to a user.

There are different types of recommenders based on how the ratings are predicted:
- Content Based Recommenders
- Collaborative Filtering System

#### Content-based
A content based recommender recommends items based on the items' features. E.g. For a book, features could be name, description, genre, author's name etc. So, a user is recommnded books that are similar to the books user has interacted with, where similarity among the books are calculated using books' features. 

#### Collaborative Recommender
A collaborative recommender recommends items based on user's historical preferences/interactions.  

#### Hybrid recommender system 
Combines multiple algorithms to create a hybrid for better performance.

