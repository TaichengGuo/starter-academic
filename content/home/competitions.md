+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 60  # Order that this section will appear.

title = "Competitions"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "KDD Cup 2020 Regular Machine Learning Competition Track "
  company = "2nd place"
  company_url = "https://tianchi.aliyun.com/competition/entrance/231785/rankingList/Final"
# location = "California"
  date_start = "2020-03-01"
  date_end = "2020-06-01"
  description = """
  * Participated in KDD Cup 2020 on how to build a recommendation system for rarely exposed items to combat Matthew effects, and **finally ranked 2nd among 1895 teams.**
  * Conducted research on multiple aspects of each component in a recommendation system: for retrieval part, investigated item-item based collaborative filtering, user-user based collaborative filtering, graph-based embedding representation, and employed Faiss for ANN search; for the ranking stage, researched on proper feature engineering and the ensemble of simple statistical models such as lightGBM, DIN and wide&deep models; in the final reranking stage, creatively designed a specific reranking algorithm for rarely viewed products.
  """

[[experience]]
  title = "NeurIPS 2020 Black-Box Optimization Challenge "
  company = "31st place worldwide (1st place in the public leaderboard)"
#  company_url = "https://bbochallenge.com/leaderboard"
# location = "California"
  date_start = "2020-07-01"
  date_end = "2020-10-01"
  description = """
  * Participated in NeurIPS challenge, and ranked 31st worldwide (1st place in the public leaderboard).
  * Proposed a warm-starting Bayesian Optimization approach, combining Bayesian optimization and meta-learning
  """

[[experience]]
  title = "Kaggle NFL Prediction"
  company = "top8%"
  company_url = ""
#  location = "California"
  date_start = "2019-11-01"
  date_end = "2020-01-01"
  description = """
  * By using position and speed data of players from NFL to train a LightGBM and neural network to predict yards that a team can gain in the game.
  """

[[experience]]
  title = "Kaggle Santander Customer Transaction Prediction"
  company = "top9%"
  company_url = ""
# location = "California"
  date_start = "2019-01-01"
  date_end = "2019-04-01"
  description = """
  * Mined features from an anonymous dataset with numerical values, utilized Xgboost and LightGBM ensemble to build models, and found best parameter combination through Bayes optimization for customer future transaction prediction.
  """


+++
