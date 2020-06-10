# TobBeDessertOrNot
This is a predictive analysis using Logistic Regression model. Is based on Epicurious recipe dataset taken from Kaggle. It's an ongoing exploration, as the dataset has over 600 columns and 20,000 recipes. There's a lot more that could be learned from it. 

Here's the Kaggle link for the analysis workbook: https://www.kaggle.com/shreya2105/to-be-a-dessert-or-not

Primary question: How likely a recipe a dessert recipe given the nutritional content in it? 

To answer this, I used the nutritional columns and the ratings as explanatory variables. And 'dessert' column as the binary response variable. 

Findings: 
1. Dessert recipes had higher ratings as the model showed that increase in ratings increased the odds of a dessert recipe by 1.17 fold, or 17% more likely than any other recipe.

2. High protein content is not 'really' expected in a dessert recipe. And the model showed that. The odds of a dessert recipe went down by 19% with the increase in the protein content.

There were several other interesting findings in this dataset. 

If it piques your interest, here's the link to the dataset: https://www.kaggle.com/hugodarwood/epirecipes
