# QueraQuestionAnalysis
This Analysis is a part of Quera contest on the kaggle, where the problem statement is to predict whether two questions are similar or not.


The Dataset of this analysis is available on the kaggle platform.


This dataset is imbalance due to more number of dissimilar questions.
Also only 10K data has been used by my model to train which also affects the end accuracy score.
Initially on applying Random forest on the dataset, it was giving an accuracy of 70%.

After some advance feature engineering, like Fuzzy Features(Pattern mathing library), Token etc.

The random forest able to achieve 77% of accuracy which is quite low then the actual winner of the contest, which is 83%.
