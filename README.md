# FAKE-NEWS-CLASSIFIER #
## AIM ##
project's aim was to create a **END TO END** fake news classifier to detect fake news.

**Project Outline**

## Web-Scraping
  web scraping using **BeautifulSoup** library of python and this is the site from where i have scrapped data for the project - [Politifact Site](https://www.politifact.com/factchecks/list/?category=fake-news)
  I have attached screenshot of frst 30 rows of my scrapped dataset 
  ![Screenshot from 2021-10-29 16-02-04](https://user-images.githubusercontent.com/70663378/139423440-d0798315-f58b-4452-b1be-1938a2e9914d.png)
## Text Preprocessing 
 1. kept only alphanumeric characters, tokenizing,lowercase conversion, punctuation removal,stopwords,lemmetization
## Data Visualization
 1. word count distribution
 2. world cloud
 3. label count distribution
## Feature Enginering 
 1. Remove labels like - Pants-fire
 2. merged label Mostly True as True
 3. Mostly False as False
## Feature Selection
 1. TF-IDF vectoriser
 2. Chi-Square test to pick top most features to avoid dimensionality curse
## Modelling
 1. Logistic Regression with L1 and L2 penality (outperformed all the other classifier)
 2. MultiNomial Naive Bayes classifier
 3. Passive Aggeressive Classifier
 4. Decision Tree Classifier
 5. Random Forest Classifier
 6. XGBoost Classifier
## Evaluation Measures
 1.Plotted Confusion Matrix for all the classifier
## Results
  **Logistic Regression gave the highest accuracy**



https://user-images.githubusercontent.com/70663378/139425454-b835b29f-6194-493a-b54f-14e8d2edcce0.mp4








