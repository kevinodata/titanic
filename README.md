# titanic
This model was developed using Python v 3.7.6 with the following libraries:<br><br>
- Scikit-Learn v 0.22.1
- Pandas
- Numpy
- Matplotlib
- Seaborn
<br><br>
The primary motivations for this project were to familiarize myself with classification tasks and feature importances. I also used this task to practice data cleaning and EDA. The final tuned Random Forest Classfier produced the predictions found in the 'titanic_submission.csv' file. This csv was then uploaded to Kaggle to obtain my final accuracy score. The full breakdown of my cleaning, analysis, and results can be viewed in the titanic_classifier jupyter notebook.
<br><br>
I started with a Logistic Regression model to get a baseline accuracy and view my feature importances. After this examination, I removed some of the less important features and brought these into a Random Forest model. Using GridSearchCV, I was able to tune the RF model and gain a 2% increase in accuracy. This 
