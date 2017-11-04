# SentimentAnalysisIGNGameReviews
Sentiment Analysis of IGN Game Reviews
Predict the sentiment in game titles from the IGN game dataset. Classification outputs a class from the set of 11 classes. Classes: ('Great', 'Good', 'Okay', 'Mediocre', 'Amazing', 'Bad', 'Awful', 'Painful', 'Unbearable', 'Masterpiece')

Performing sentiment analysis using tflearn on a small number of output classes such as 2 or 3 (Positive, Negative, Neutral) would give us much higher accuracies compared to using these 11 classes.

<html>
<table>
  <tr>Result</tr>
  <tr><td>Layers</td><td>Dropouts</td><td>Train/Test split</td><td>Batch size</td><td>Accuracy</td></tr>
  <tr><td>LSTM(128), LSTM(128), LSTM(128)</td>	<td>(0.9, 0.9, 0.9)</td>	<td>0.80</td>	<td>32</td><td>40.8%</td></tr>
</html>
