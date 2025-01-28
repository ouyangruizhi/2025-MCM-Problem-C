# 2025-MCM-Problem-C
**Solution of 2025 MCM Problem C** Cracking the Olympic Medal Code: A Dual Strategy of Country Clustering and Optimal Model Selection
- Cluster Model
  We use the combined clustering strategy of **K-means + Hierarchical clustering + SOM clustering + K-means** to cluster the world countries into 4 categories and build medal prediction models respectively.  
- Medal Predict Model
  In which we compared Dummy Classifier, logistic regression, Decision Tree, KNN, XGBoost, LightGBM, Bagging, Random Forest, Stacking, Voting, 
Native Bayes with ROC curve, AUC value, Accuracy, Recall, Precision and cross-validation results, and finally determined that Cluster0, Cluster1, Cluster3 are suitable for prediction using **Bagging** modeling and Cluster2 is suitable for prediction using **LightGBM**.  
- Importance Analysis Model
  Calculating Variable Importance Based on **LightGBM** model and **MDI**.
