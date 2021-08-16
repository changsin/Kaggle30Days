# 30 Days of Kaggle

## Day1
Signing up and becoming a contributor by doing the first submission using the Titanic dataset.

## Day 2 - 7: Python
Going over Python syntax. For me, these were just a review.

## Day 8 - 11: Intro to ML
### Day 8:
- [How models work? (Lesson 1)](https://www.kaggle.com/dansbecker/how-models-work)
- Basic data exploration - intro to pandas library (Lesson 2)
### Day 9:
- [Your first ML Model (Lesson 3)](https://www.kaggle.com/dansbecker/your-first-machine-learning-model)
- Validation (Lesson 4)
### Day 10:
- [Underfitting and Overfitting (Lesson 5)](https://www.kaggle.com/dansbecker/underfitting-and-overfitting)
  - Overfitting: capturing spurious patterns that won't recur in the future, leading to less accurate predictions, or
  - Underfitting: failing to capture relevant patterns, again leading to less accurate predictions.
- [Random Forests (Lesson 6)](https://www.kaggle.com/dansbecker/random-forests?utm_medium=email&utm_source=gamma&utm_campaign=thirty-days-of-ml&utm_content=day-10)
  "The random forest uses many trees, and it makes a prediction by averaging the predictions of each component tree. It generally has much better predictive accuracy than a single decision tree and it works well with default parameters. If you keep modeling, you can learn more models with even better performance, but many of those are sensitive to getting the right parameters."
  
### Day 11: ML Competitions
The course finishes with an optional [intro to AutoML](https://www.kaggle.com/alexisbcook/intro-to-automl). It uses Google's [AutoML Tables](https://cloud.google.com/automl-tables) 

## Day 12 - : [Intermediate ML](https://www.kaggle.com/learn/intermediate-machine-learning)
### Day 12 (2021-08-14 Sat)
- Lesson 1: [Introduction](https://www.kaggle.com/alexisbcook/introduction?utm_medium=email&utm_source=gamma&utm_campaign=thirty-days-of-ml&utm_content=day-12)
- Lesson 2: [Missing Values](https://www.kaggle.com/alexisbcook/missing-values)
  Three ways to handle missing values
  1. Drop the table with missing values
  2. Imputation: fills in the missing values with some number.
  3. Imputation Extra: Add extra info (feature) about the imputation
- Lesson 3: [Categorical Variables](): Three ways to handle categorical values
  1. Drop categorical variables
  2. Ordinal encoding: works well with ordinal values - when some kind of ranking is involved
  3. One-hot encoding: works well for no clear ordering: i.e., 'nominal values' (variables with no ranking)
  Cardinality: the number of unique entries in categorical variables.
  The final submission improved the ranking ot 4491 in https://www.kaggle.com/c/home-data-for-ml-course/leaderboard#score

### Day 13 (2021-08-15 Sun)
- Lesson 4: [Pipelines]
- Lesson 5: [Cross-Validation]
