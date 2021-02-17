# StumbleUpon-Classification
The aim is to identify whether a given website is ephemeral or evergreen
### Steps - 
* Create a function
* in this function, first data set is loaded for both train and test
* Next if we check the data boilerplate is the usable column amongst rest , so we consider for 'boilerplate' column for both train and test separately
* 'Urlid' is required for submission file as according to the ids label will be assigned.
* We clean the train and test data containing only 'boilerplate' content
* then we combine or merge the train and test into one.
* Now my aim is to further preprocess this combined data to remove stopwords and further parameters using TfidfVectorizer. This vectorizer is used to convert the texual data to vectors for the machine to understand as text data can't be interpreted by machine. Stopwords are used as these words serve no useful purpose and can sometimes lead to miscalculations
* Now we can separate or split our this combined data into new train and test data for fitting and predicting labels for test data.
* We can use any classification algo, but I used Logistic Regression(LR). LR is a predictive analysis algo based on probability concepts.
* Further I have calculated the Cross validation score to evaluate the model's performance
* Then finally the train data is fitted and then the model is used to predict on test data
* At the last, classification report is computed which describes the precision, recall and f1 score.

# Classification Report - ![Screen Shot 2021-02-17 at 6 03 18 PM](https://user-images.githubusercontent.com/44721225/108205149-aaae4b80-714a-11eb-9eab-0eb937c889e8.png)
