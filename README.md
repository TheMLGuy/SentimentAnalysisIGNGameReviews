# SentimentAnalysisIGNGameReviews
Sentiment Analysis of IGN Game Reviews
Predict the sentiment in game titles from the IGN game dataset. Classification outputs a class from the set of 11 classes. Classes: ('Great', 'Good', 'Okay', 'Mediocre', 'Amazing', 'Bad', 'Awful', 'Painful', 'Unbearable', 'Masterpiece')

Performing sentiment analysis using tflearn on a small number of output classes such as 2 or 3 (Positive, Negative, Neutral) would give us much higher accuracies compared to using these 11 classes.

Result
Layers                           Dropouts       Train/Test split    Batch size    Accuracy
LSTM(128), LSTM(128), LSTM(128)	(0.9, 0.9, 0.9)	0.80	              32	          40.8%
