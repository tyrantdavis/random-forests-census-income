# Building a Random Forest - Census Income

## [Demo](https://nbviewer.org/github/tyrantdavis/random-forests-census-income/blob/main/random-forest.ipynb)

## Scenario
Professors at a college are eager to integrate machine learning into their respective disciplines. The Economics department aims to enhance students' understanding of the interactions among various income factors. In this project, the task is to determine if an individual's income surpasses $50,000 per year using census data as a basis for the predictions.


**Data Sources:**

- [Census Income](https://archive.ics.uci.edu/dataset/20/census+income)

## Project Goals
The initial objective is to determine if an individual's income surpasses $50,000 per year using census data as a basis for your prediction.

Several questions will be asked:

1. What feature contriuted the most to the outcome?
2. How accurate is the Random Forest model?
3. What advantage does a random forest have over a single decision tree?
4. What percentage of samples have incomes less than 50k and greater than 50k?
   



#### Why use a Random Forest model to predict the classification?
Ensemble learning is a fascinating approach in machine learning that combines the predictions from several models to enhance overall accuracy. By leveraging the strengths of multiple models, this technique aims to produce more reliable predictions than any single model could achieve on its own. When different models, particularly those that vary in their design, are brought together, the result is often a significant improvement in estimation quality.

One popular example of ensemble learning is the random forest method, which merges the outputs of numerous decision tree models. In this approach, the final decision can be determined by either taking the most common classification from all the trees or calculating the average of their predictions for regression tasks.


## Data
A dataset that can be used to train the machine-learning model has been found. It is a CSV file containing 32561 census records. 


## Conclusions
TBD...

1. What feature contriuted the most to the outcome?
    - capital-gain 
2. How accurate is the Random Forest model?
    - The greatest accuracy is 84.4% at a max_depth of 9 which was an increase from the initial model at 83.5.
3. What advantage does a random forest have over a single decision tree?
    - Decision trees often tend to fit too closely to the training data, which can lead to overfitting. In contrast, random forests help to lower this variance, making them a great option for addressing overfitting challenges.\

6. What percentage of samples have incomes less than 50k and greater than 50k?
    - less than or equal to 50k ~ 76%
    - greater than 50k ~ 24%
