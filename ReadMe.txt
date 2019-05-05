The task is to predict whether a song was a ‘hit’, meaning that it made it onto the Billboard Top 50 — each instance has a label “Hit?” equal to “yes” (1) or “no” (0). The attributes are: year of release(multi-valued discrete, range [1900,2000]), length of recording (continuous, range [0,7]), jazz (binary discrete, “yes”/“no”), rock and roll (binary discrete, “yes”/“no”).
For performing above task, we are using both Gradient descent and Stochastic gradient descent

We have been provided with attributes and labels split into training and development data in files music*.csv
• music_train.csv: attributes for training data, without labels, with
column names on the first line
• music_train_keys.txt: labels for training data, as a single
column with no column names
• music_dev.csv: attributes for development data, without labels, with
column names on the first line; shares the same format (but not necessarily the same number
of records) as the test set that you will be evaluated on
• music_dev_keys.txt: labels for development data, as a single
column with no column names