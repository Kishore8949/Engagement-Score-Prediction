# Engagement-Score-Prediction

**Objective**:

1. Predicting the Engagement Score Prediction.

**Dataset Description**:

  user_id     : Unique ID value representing a User.

  category_id : Unique ID value for a category of movie.

  video_id    : Unique ID value of a movie.

  age         :   Age of the User.

  Gender      : Gender of the User.

  Profession  : Profession of the User.

  followers   : Followers for a paticular Category ID.

  views       : Total views of a particular Video ID

  engagement_score : The Engagement score of a User Based on the independant Variables
  

**Collaborative Based Recommendation**

Using SVD ++ Algorithm(The SVD++ algorithm, an extension of SVD taking into account implicit ratings), Hyper Parameter tuning using optuna.

This submission got 0.495 r2score on public test data.




