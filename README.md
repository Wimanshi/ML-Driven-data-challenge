# ML-Driven-data-challenge
# 170011B
Github link :- https://github.com/Wimanshi/ML-Driven-data-challenge.git
## Pump it Up: Data Mining the Water Table Challenge
### Our goal was to predict the operating condition of a waterpoint for each record in the dataset given.
### After downloading datasets, read the datasets by importing the datasets.
### Then there were missing values in the dataset. So, handled the missing values by dropping some unwanted columns and replace null values by mean or median.

### These are the Dropped features
* `Funder`
* `Subvillage`
* `scheme_name`

### These are the Replace null values by mean or median
* `installer`
* `public_meeting`
* `scheme_management`
* `permit`

### Used CatBoost Classifier in Python to get the results
### Then I declared the feature vectors for the classifier and the “cat_features” array.

### This is the model I used here,
### model = CatBoostClassifier(iterations=1000, learning_rate=0.1, depth=5, loss_function='MultiClass')

## Submission
![Screenshot (86)](https://user-images.githubusercontent.com/47114903/133835895-22cb4809-03e9-4dcd-8afb-0837d7926d09.png)
