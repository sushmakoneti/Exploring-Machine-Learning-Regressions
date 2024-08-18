Explored all the regression model's for the Auto Mpg Kaggle Dataset:

In the quest to find the best model for predicting MPG using the Auto MPG dataset, I experimented with a variety of regression techniques. The objective was not only to see which model could make the most accurate predictions but also to understand how different models handle the complexities of the data. From traditional linear models to advanced machine learning algorithms, each approach was put to the test, offering unique insights into their capabilities and limitations.

Dataset link:
https://www.kaggle.com/datasets/uciml/autompg-dataset/code?datasetId=1489&searchQuery=regression

After evaluating all the regression models on the Auto MPG dataset, Random Forest Regression and Gradient Boosting Regression emerged as the top performers. These models delivered the most accurate predictions, with Random Forest achieving the lowest error (MSE of 5.72) and the highest R² score (0.89), meaning it explains most of the variance in the data. These results suggest that Random Forest is particularly good at capturing the complexities in the data.

KNN Regression also did well, with an MSE of 7.23 and an R² of 0.86, proving to be a strong contender, especially for non-linear relationships. The MLP Regressor showed promise but required more tuning to reach its full potential.

On the other hand, simpler models like Linear Regression, Lasso, and Ridge Regression were easier to understand and interpret, though they didn’t capture the data's nuances as effectively. Their MSE values hovered around 10.7, with R² scores around 0.79, making them decent but not the best options for this dataset.

In the end, if accuracy is your main goal, Random Forest or Gradient Boosting would be the best choices. But if you need something straightforward and easy to explain, Linear Regression or its variations are still solid options.
