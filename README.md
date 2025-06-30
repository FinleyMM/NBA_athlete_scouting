## K-Means Clustering, K-Nearest Neighbors (KNN), Linear Regression, BisectingKMeans, and Support Vector Machine (SVM) on NBA Player Dataset

This project implements various machine learning models to analyze NBA player statistics using PySpark. It clusters players, predicts positions, models 3-point percentages, and classifies performance metrics. The dataset is preprocessed, models are trained and evaluated, and results are visualized.

-**Data Preprocessing:** Selected features (`Age`, `G`, 'GP', ' FG', '3P', 'MP'), handled missing values, and assembled using VectorAssembler.

-**Models Used:** K-Means Clustering, K-Nearest Neighbors (KNN), Linear Regression, BisectingKMeans, Support Vector Machine (SVM).

-**Evaluation Metrics:** Silhouette Score (clustering), Accuracy (KNN/SVM), RMSE (Linear Regression).

-**Visualisations:** Scatter plot for actual vs. predicted 3P%, confusion matrix for SVM.

-**Hyperparameter Tuning:** Basic parameter setting (e.g., K=2 for KMeans), with potential for expansion.

Can be used for player prototypes, player performance prediction, NBA Draft Scouting and player/team compatability.
