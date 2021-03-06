# Sentiment Analysis using Logistic Regression

## Amazon Fine Food Review dataset
Data Source:  https://www.kaggle.com/snap/amazon-fine-food-reviews

EDA: https://nycdatascience.com/blog/student-works/amazon-fine-foods-visualization/ <br>
<br>
<b>The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.</b>
<br>
<li>Number of reviews: 568,454</li>
<li>Number of users: 256,059</li>
<li>Number of products: 74,258</li>
<li>Timespan: Oct 1999 - Oct 2012</li>
<li>Number of Attributes/Columns in data: 10</li>
<br>
<b>Attribute Information:</b>
<br>
<li>Id</li>
<li>ProductId - unique identifier for the product</li>
<li>UserId - unqiue identifier for the user</li>
<li>ProfileName</li>
<li>HelpfulnessNumerator - number of users who found the review helpful</li>
<li>HelpfulnessDenominator - number of users who indicated whether they found the review helpful or not</li>
<li>Score - rating between 1 and 5</li>
<li>Time - timestamp for the review</li>
<li>Summary - brief summary of the review</li>
<li>Text - text of the review</li>

## Objective:
Given a review, determine whether the review is positive (rating of 4 or 5) or negative (rating of 1 or 2).
<br>

### [Q] How to determine if a review is positive or negative?
<br>
[Ans] We could use Score/Rating. A rating of 4 or 5 can be cosnidered as a positive review. A rating of 1 or 2 can be considered as negative one. A review of rating 3 is considered nuetral and such reviews are ignored from our analysis. This is an approximate and proxy way of determining the polarity (positivity/negativity) of a review.
