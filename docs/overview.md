# Predicting House Prices

![](https://kaggle2.blob.core.windows.net/competitions/kaggle/5407/media/housesbanner.png)

## Description

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

In this task, you are going to predict the final price for each home. The dataset contains 79 variables describing (almost) every aspect of residential homes. 

## Evaluation

It is your job to predict the sales price for each house. For each Id in the test set, you must predict the value of the SalePrice variable. At the end of this challenge, you only have one chance to submit the prediction for the test data. You may use methods like cross-validation to evaluate your algorithm during the study phase.

### Metric

Submissions are evaluated on [Root-Mean-Squared-Error (RMSE)](https://en.wikipedia.org/wiki/Root-mean-square_deviation) between the logarithm of the predicted value and the logarithm of the observed sales price. (Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.)

### Submission

Please follow the [instructions](submission.md).