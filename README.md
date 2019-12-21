# Food-and-Recipies-Data-Analysis

Please download two data set file from kaggle 

RAW_interactions : https://www.kaggle.com/shuyangli94/food-com-recipes-and-user-interactions#RAW_interactions.csv

RAW_recipes : https://www.kaggle.com/shuyangli94/food-com-recipes-and-user-interactions#RAW_recipes.csv

This data is of https://www.food.com/
Food.com is a place where you can find recipies for all ocassions. It is a social networking platform for people who like to try new recipes and people who like to make new recipes.

The website has a lot of features that attract people and retain them. There are sections where you can find ratings and reviews for the recipes which makes it perferct for people to double-check that is the recipe they want.

The data from kaggle website has Recipes, Interactions and User information. We are only considering Recipes and Interactions for our analysis. Interations being the reviews and ratings posted for each recipe.

![API Output](https://github.com/SONAMDAWANI/Food.com-Data-Analysis_Data-Mining-Project/blob/master/Image/Fooddotcom.png)


WHAT THIS PROJECT DO?

We started with selecting interesting data. We choose data of Food.com from kaggle. To understand the data first we did the data analysis, where we saw different data files and there length, central tendency metric for various columns/features, the relation between the features and the outlier analysis. Once we analyzed the data and saw the issues, we worked upon to resolve them by handling outliers.

Then we started with classification where we introduced the new column as Cusine for our data set. Using the new column we analysed our data and came up with interesting analysis. Second, we performed clustering over the ingredients, for that we performed PCA, vectorization and K-means. Analysing cluster over rating and review provides us with meaningful insights. After that, we saw regression where by help of Carbs and Calories we predected other nutritional values using Gradient Boosting Regression. Last but not the least we performed Market Basket Analysis which can be profitable for the sales.


Please check the below notebook for details:
https://github.com/SONAMDAWANI/Food-and-Recipies-Data-Analysis_Data-Mining-Project/blob/master/DM_Project_Code.ipynb
