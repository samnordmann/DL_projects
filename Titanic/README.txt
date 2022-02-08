link to the notebook: https://www.kaggle.com/samuelnordmann/titanic-binary-classification

In this notebook I present a studycase of binary classification on the Titanic dataset. The task consists in predicting what passenger survived in the Titanic crash.

This dataset is classical and largely studied. Here, I propose my own original solution achieving 77.8% accuracy on the test set, which ranks in the top 25% of the 13k+ Kaggle challengers at time of submission.

Most of the work lies in the data engineering that I detail and try to explain as clearly as possible. Then, I train a XGB Classifier on 7 features selected by Mutual Information score.
