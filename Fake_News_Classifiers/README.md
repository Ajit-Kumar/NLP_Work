
In the following analysis, we will talk about how one can create an NLP to detect whether the news is real or fake. Nowadays, fake news has become a common trend. Even trusted media houses are known to spread fake news and are losing their credibility. So, how can we trust any news to be real or fake?

Dataset

train.csv: A full training dataset with the following attributes:

id: unique id for a news article

title: the title of a news article

author: author of the news article

text: the text of the article; could be incomplete

label: a label that marks the article as potentially unreliable. Where 1: unreliable and 0: reliable.


Methods Used

1.Bags of word for extracting featues.
2.TF-IDF

Classifiers Used

RandomForest
Naive Bayes
SVC
PassiveAggressiveClassifier
