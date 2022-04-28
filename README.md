# Machine-Learning and Natural Language Processing:

### Supervised Learning:
* Linear regression:
    * student_scores.csv (simple Linear regression)
    * petrol_consumption.csv ((Multiple Linear regression))
    * Ridge regression
    * Feature Selection:
        * RFE - Repeated Feature Elimination
        * Sequential Feature selection
     * Cross Validation
     * Effect of Outlier
* Logistic regression:
    * Credit card fraud detection
    * predicted probablity (log_reg.predict_proba(X_test))
* k-nearest neighbours:
    * ushape.csv, concertriccir2.csv, xor.csv, linearsep.csv.
* Naive Bayes algorithm:
    * Social_Network_Ads.csv
    * predicted probablities (GaussianNB.predict_proba(X_test))
* Decision Tree:
    * wbc.csv (for Classifier), auto-mpg.csv (for Regressor)
    * predicting the probablities (dt.predict_proba(X_test))
    * Feature Importances:
        * dt.feature_importances_
* Ensemble techniques:
    * Bagging - Bootstrap aggregation
        * “VotingClassifier” module (by creating pipeline - DT Classifier,Log-reg, KNN-Classifier)
        * Weighted Voting (assigning weights to each model)
        * Random Forest algorithm - temps.csv
           * RandomForestRegressor
           * Variable Importances (rf.feature_importances_)
    * Boosting :
        * Gradient boosting - GradientBoostingRegressor
        * XGBoost
* Imbalanced dataset:
    * Masked dataset
    * Credit card fraud detection
  
### Unsupervied Learning:
* K-means clustering:
    * kmeans_faithful.csv
    * Can only learn spherical  (with Eucleadian distance metric)

### Natural Language Processing:
* IMDB sentiment analysis
