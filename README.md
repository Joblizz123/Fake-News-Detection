# Fake-News-Detection
This project is about detecting fake news on the net and other news related platforms. 
There are two different datasets used- the fake news and the confirmed news datasets respectively.They were sourced from kaggle.The datasets were loaded and examined; they are quite large- about 43, 000 combined records. Missing records and duplicates were checked and sorted out. The two datasets were merged into a single dataframe, and the less important features (title and date) removed. The categorical fake and true classes were label encoded, 1 meaning fake and 0 true. 
The combined dataframe was then split into training and test sets.Tf-Idf vectorizer was applied to the training aqnd test feature(s)  to vectorize the categorical texts. 
MultinomialNB naive bayes algorithm was preferred for this problem.
The model was then evaluated using the test set. From the classification report, the model's score are summarised as: 94% accuracy, 96% and 92% precision for fake (1) and true (0) classes, 90% and 97% recall values for fake and true classes, 93% and 94% F1-score and 94% accuracy score.
I tried to create a Prediction System, and the model did just great!
