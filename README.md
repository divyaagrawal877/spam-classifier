# spam-classifier
A program to classify mail into ham and spam

We first do data exploration to find out what our data looks like. What do spam mails have in common? What are the more frequently used words in spam mails.
We then do the following
* Convert html text to plain text
* Stemming to reduce the word into its root

We train a logistic regression model using cross validation to find the most suitable hyperparameters.
We measure the performance of the model using precision and recall scores.

