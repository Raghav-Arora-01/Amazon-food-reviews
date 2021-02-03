# Amazon-food-reviews

> Given a review, determine whether the review is positive (Rating of 4 or 5) or negative (rating of 1 or 2)

Data Source: https://www.kaggle.com/snap/amazon-fine-food-reviews

The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.

     Number of reviews: 568,454  
     Number of users: 256,059
     Number of products: 74,258
     Timespan: Oct 1999 - Oct 2012
     Number of Attributes/Columns in data: 10 

**Attribute Information:**

    1) ProductId - unique identifier for the product
    2) UserId - unqiue identifier for the user
    3) ProfileName -Profile name of the customer
    4) HelpfulnessNumerator - number of users who found the review helpful
    5) HelpfulnessDenominator - number of users who indicated whether they found the review helpful or not
    6) Score - rating between 1 and 5
    7) Time - timestamp for the review
    8) Summary - brief summary of the review
    9) Text - text of the review

**Objective:**
   # Classification of Amazon-Reviews into two categories (Positive or Negative) Using LSTM

**Note :**
    Here we are purposefully ignoring reviews with score equals to 3 as there are Neutral , and if the score is above 3 then the  review will be set to "Positive" , otherwise it will be set to "Negative".  
