In this short project, I take a look at customer satisfaction surveys.

Goals: 
1. Build a model that achieves >73% accuracy in predicting if a customer is truly happy or not based on the survey results.
2. Identify insignificant features (survey questions) that may be excluded in future surveys.

I achieved an accuracy of 76%, and f1-scores of 0.69 and 0.80 for the unhappy and happy customers, respectively.

Two important steps in feature engineering were to remove outliers and then reduce each survey question into a binary value, where each question had its own threshold by which the data were transformed.

The final model included 2 classifiers combined using nearly equal weights in a soft Voting Classifier.

The features of least importance stem from survey questions related to the expected content of the order and price.

C06v7wu6wOp0jh6C
