# Sentiment Analysis using Logistic Regression
Step by step implementation of using logistic regression for sentiment analysis of Amazon fine food review

## Amazon Fine Food Reviews Analysis
Data Source:  https://www.kaggle.com/snap/amazon-fine-food-reviews

EDA: https://nycdatascience.com/blog/student-works/amazon-fine-foods-visualization/ <br>
<br>
The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.
<br>
<li>Number of reviews: 568,454</li><br>
<li>Number of users: 256,059</li><br>
<li>Number of products: 74,258</li><br>
<li>Timespan: Oct 1999 - Oct 2012</li><br>
<li>Number of Attributes/Columns in data: 10</li> <br>
<br>
Attribute Information:
<br>
Id<br>
ProductId - unique identifier for the product<br>
UserId - unqiue identifier for the user<br>
ProfileName<br>
HelpfulnessNumerator - number of users who found the review helpful<br>
HelpfulnessDenominator - number of users who indicated whether they found the review helpful or not
Score - rating between 1 and 5<br>
Time - timestamp for the review<br>
Summary - brief summary of the review<br>
Text - text of the review<br>

## Objective:
Given a review, determine whether the review is positive (rating of 4 or 5) or negative (rating of 1 or 2).
<br>

### [Q] How to determine if a review is positive or negative?
<br>
[Ans] We could use Score/Rating. A rating of 4 or 5 can be cosnidered as a positive review. A rating of 1 or 2 can be considered as negative one. A review of rating 3 is considered nuetral and such reviews are ignored from our analysis. This is an approximate and proxy way of determining the polarity (positivity/negativity) of a review.
