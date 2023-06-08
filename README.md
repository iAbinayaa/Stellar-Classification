# Stellar-Classification

The Stellar Classification project was an in-depth exploration into the realm of astronomical data analysis, with a primary focus on star classification. The objective of this project was to use machine learning models to predict the class of a star based on several features provided in a dataset. 

The initial phase involved preprocessing the dataset using various methods from the sklearn library. These preprocessing stages encompassed scaling, encoding, and data cleaning, among other necessary steps to prepare the data for model implementation. Part of the process included handling missing values, outliers, and potential skewness in the data, ensuring that the data adhered to the requirements of the subsequent machine learning phase.

After preprocessing, the dataset was split into two subsets, where 75% was used for training the models, and the remaining 25% was reserved for testing. This division provided a robust foundation for both training and evaluating the implemented models' performance.

The machine learning phase involved using a range of models. The k-Nearest Neighbors (KNN) classifier was used, which classified stars based on similarity measures (distance functions). Logistic Regression was also implemented to model the probabilities of a certain class given a set of feature inputs. Decision Tree Classifier and Random Forest Classifiers were employed as well. These algorithms work by constructing decision trees and ensemble methods respectively, hence, adding more depth and diversity to the project. 

The final stage involved applying boosting techniques to improve the model's performance further. Boosting is a method of converting a set of weak learners into a strong learner, which significantly improved the accuracy of the classification. 

The Stellar Classification project demonstrated a comprehensive application of machine learning algorithms to classify stars, utilizing a variety of techniques to optimize the predictive power of the models. It provided a valuable resource for understanding how machine learning can be applied to astronomical datasets and offered insights into effective preprocessing, model implementation, and the use of boosting techniques.
