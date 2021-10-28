



# web-scraping from politifact website by using beautiful soup library
  website link for scraping of data - [Politifact Site](https://www.politifact.com/factchecks/list/?category=fake-news)
# text preprocessing 
 1. tokenizing,lowercase conversion, punctuation removal,stopwords,lemmetization
 2. removal of unnecessary labels from label column except fake and true 
# data visualization
 1. word count distribution
 2. world cloud
 3. label count distribution
# feature selection
 1. TF-IDF vectoriser
 2. Chi-Square test
# modelling
 1. Logistic Regression with L1 and L2 penality (outperformed all the other classifier)
 2. MultiNomial Naive Bayes classifier
 3. Passive Aggeressive Classifier
 4. Decision Tree Classifier
 5. Random Forest Classifier
 6. XGBoost Classifier
# plotted confusion matrix for all the models

https://user-images.githubusercontent.com/70663378/139210962-702daf3a-e36d-48fc-93f9-5adca3d7c61e.mp4![fake-news2](https://user-images.githubusercontent.com/70663378/139214896-d6716c9d-3246-457b-a408-0d2fadfa5542.png)
