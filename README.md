# Fake_news_detection_PassiveAggressiveClassifier
About Detecting Fake News with Python: 

This advanced python project of detecting fake news deals with fake and real news. Using sklearn, I build a TfidfVectorizer on the dataset.
Then, I initialize a PassiveAggressive Classifier and fit the model. In the end, the accuracy score and the confusion matrix tell  how well  model fares.
**PassiveAggressiveClassifier**:
to detect fake news on a social media website like Twitter, where new data is being added every second. To dynamically read data from Twitter continuously, the data would be huge, and using an online-learning algorithm would be ideal.

Passive-Aggressive algorithms are somewhat similar to a Perceptron model, in the sense that they do not require a learning rate. However, they do include a regularization parameter.

**How Passive-Aggressive Algorithms Work:**
**Passive-Aggressive algorithms are called so because :**

Passive: If the prediction is correct, keep the model and do not make any changes. i.e., the data in the example is not enough to cause any changes in the model. 
Aggressive: If the prediction is incorrect, make changes to the model. i.e., some change to the model may correct it.
