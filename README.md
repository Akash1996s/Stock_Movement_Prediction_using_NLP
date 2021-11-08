# Stock_Price_Prediction_using_BagOfWords
* This project is to predict the movement of stock price as per top news headlines.

The top 25 headlines were collected day wise and the movement of stock increased (1) or drop (0).

## Data preporcessing :
1. Removed Special Characters using regular expression.
2. Removed stopwords using nltk library and tokennizer.
3. Lower all the characters in the data.
4. Joining all the headlines day wise to make a document.
5. The data was converted to "Bag of Words" using CountVectorizer.

## ML Modeling:
1. Random Forest Classifier was giving the best accuracy score.

