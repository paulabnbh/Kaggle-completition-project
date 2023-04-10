# Kaggle-completition-project

![portada](https://github.com/paulabnbh/Kaggle-completition-project/blob/main/img/salary-img.jpg)

#### GOAL
The goal of this project is to create the most accurate prediction of data jobs salaries through Machine Learning models in a Kaggle competition. The documentation given for the competition is:
+ a csv file with features of different jobs and its salaries.
+ a csv file with features of different jobs but no salaries.
+ a csv file with an example of prediction.

####  CLEANING PROCESS

We can find two different cleaning documents in the repository:
+ in one of the document the cleaning process consisted on using Label Encoder in order to turn all the categorical data into numerical data.
+ in the other document, the cleaning process was the same, except or the *job_title* column, which I labeled the top 10 and the rest shared one label.


#### PREDICTION

Once the cleaning process was finished in both documents I used LazyRegressor() to know what regression model would fit the best for each dataset. I used different prediction models in each of the cleaned datasets and the best result was Poisson.
