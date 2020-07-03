Titanic Survival - Kaggle Project
--------------------------------

The objectif of this Project is to predict whether a passenger survived or not in the Titanic shipwreck. Given some predictive variable, we have to implement a model that allow us to classify correctly the passengers. For more detail about


Files
--------------------------------
* `Titanic_Data_Analysis.ipynb` : Jupyter notebook containing the code used.
* `train.csv` : Training data
* `test.csv` : Test data


Frameworks
--------------------------------
* `Pandas` : Data Wrangling/Data Analysis
* `Seaborn` : Data Visualization
* `Scikit-learn` : Machine learning Model / Metrics


Model - Metrics
--------------------------------
* The best final model used is : `Logistic Regression`
	* We chose this model on the basis of `Learning Curves` cf. Jupyter notebook
* `xgboost` algorithm perform better in the validation set but poorly in a new dataset (`test.csv`) due to `overfitting`.
* Metrics : `f1-score`


Accuracy - Rank 
--------------------------------
* Our model perform on the `test.csv` with an accuracy of  `~78%`
* Rank : 5,625/23354 - `Top 25%`


Work Progress 
--------------------------------
* Improving accuracy by :
	* Finding new features.
	* Tuning hyperparameters.


