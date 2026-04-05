# ST554_HW8

I add **homework 8** on the bottom of homework 7. The Homework 7 notebook is reused to avoid repeating data ingestion, cleaning, and exploratory data analysis. This allows Homework 8 to focus on model building and performance evaluation.

The purpose of this homework is to practice fitting tree based models using `csikit-learn`.
We will use the `Wine Quality` dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/186/wine+quality) that we used in hommwork 7. The variables in the dataset based on physicochemical tests include:
- fixed acidity: g(tartaric acid)/dm3
- volatile acidity: g(acetic acid)/dm3
- citric acid: g/dm3
- residual sugar: g/dm3
- chlorides: g(sodium chloride)/dm3
- free sulfur dioxide: mg/dm3
- total sulfur dioxide: mg/dm3
- density: g/cm3
- pH
- sulphates: g(potassium sulphate)/dm3
- alcohol: (vol.%)
- quality: score between 0 to 10
Detialed information can be found in Cortez et al. (2009).

We will use `alcohol` as a target variable for fitting regression type models while using `type of wine` as the response variable for fitting classification type models.

We will compare all of (including homework 7) models performance.
