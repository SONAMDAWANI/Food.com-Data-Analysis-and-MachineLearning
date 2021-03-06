Hey there!
I am Sonam Dawani. 

For any question, concern or suggestion, please connect with me on [Linkedin](https://www.linkedin.com/in/sonamdawani/)

# Food-and-Recipies-Data-Analysis

## Project Agenda
For the dataset of https://www.food.com/
Food.com is a place where you can find recipies for all ocassions. It is a social networking platform for people who like to try new recipes and people who like to make new recipes.

 - Exploratory Data Analysis
 - Data Processing / Data Cleaning
 - Classification to introduce the new column as Cusine AND draw meaningful insights
 - Clustering over the ingredients AND draw meaningful insights
 - Regression to predict nutrition values (like Fat) from carbs and calories
 - Market Basket Analysis to increase revenue
 
## Dataset
Please download two data set file from kaggle 

RAW_interactions : https://www.kaggle.com/shuyangli94/food-com-recipes-and-user-interactions#RAW_interactions.csv

RAW_recipes : https://www.kaggle.com/shuyangli94/food-com-recipes-and-user-interactions#RAW_recipes.csv

## Food.com Overview
The website has a lot of features that attract people and retain them. There are sections where you can find ratings and reviews for the recipes which makes it perfect for people to double-check that is the recipe they want.

The data from kaggle website has Recipes, Interactions and User information. We are only considering Recipes and Interactions for our analysis. Interations being the reviews and ratings posted for each recipe.

![API Output](https://github.com/SONAMDAWANI/Food.com-Data-Analysis_Data-Mining-Project/blob/master/Image/Fooddotcom.png)


## Project walk through

### Python libraries used:
##### pandas, numpy, sklearn, scipy, matplotlib, seaborn, nlkt, apyori


We started with selecting interesting data. We choose data of Food.com from kaggle. 

- To understand the data first we did the data analysis, where we saw different data files and there length, central tendency metric for various columns/features, the relation between the features and the __outlier analysis__. 

- Once we analyzed the data and saw the issues, we worked upon to resolve them by handling outliers.

- Then we started with __classification__ where we introduced the new column as Cusine for our data set. Using the new column we analysed our data and came up with interesting analysis. 
Used __RandomForestClassifier__ for classification, tuned the parameters using __GridSearchCV__ and accomplished the F1 score as 0.75

- Second, we performed clustering over the ingredients, for that we performed __PCA__, __TF_IDF__ vectorization and __K-means__. 
Analysing cluster over rating and review provides us with meaningful insights. 

- After that, we saw regression where by help of Carbs and Calories we predected other nutritional values using __Gradient Boosting Regression__. 

- Last but not the least we performed __Market Basket Analysis__ using __Apriori algorithm__ which can be profitable for the sales.

![alt text](https://github.com/SONAMDAWANI/Food.com-Data-Analysis_Data-Mining-Project/blob/master/Presentation/Slide1.jpeg?raw=true
      )
      
![alt text](https://github.com/SONAMDAWANI/Food.com-Data-Analysis_Data-Mining-Project/blob/master/Presentation/Slide2.jpeg?raw=true
      )
      
![alt text](https://github.com/SONAMDAWANI/Food.com-Data-Analysis_Data-Mining-Project/blob/master/Presentation/Slide3.jpeg?raw=true
      )
      
![alt text](https://github.com/SONAMDAWANI/Food.com-Data-Analysis_Data-Mining-Project/blob/master/Presentation/Slide4.jpeg?raw=true
      )
      
![alt text](https://github.com/SONAMDAWANI/Food.com-Data-Analysis_Data-Mining-Project/blob/master/Presentation/Slide5.jpeg?raw=true
      )
      
![alt text](https://github.com/SONAMDAWANI/Food.com-Data-Analysis_Data-Mining-Project/blob/master/Presentation/Slide6.jpeg?raw=true
      )
      
![alt text](https://github.com/SONAMDAWANI/Food.com-Data-Analysis_Data-Mining-Project/blob/master/Presentation/Slide7.jpeg?raw=true
      )
      
![alt text](https://github.com/SONAMDAWANI/Food.com-Data-Analysis_Data-Mining-Project/blob/master/Presentation/Slide8.jpeg?raw=true
      )
      
![alt text](https://github.com/SONAMDAWANI/Food.com-Data-Analysis_Data-Mining-Project/blob/master/Presentation/Slide9.jpeg?raw=true
      )
      
![alt text](https://github.com/SONAMDAWANI/Food.com-Data-Analysis_Data-Mining-Project/blob/master/Presentation/Slide10.jpeg?raw=true
      )
      

![alt text](https://github.com/SONAMDAWANI/Food.com-Data-Analysis_Data-Mining-Project/blob/master/Presentation/Slide11.jpeg?raw=true
      )
      
![alt text](https://github.com/SONAMDAWANI/Food.com-Data-Analysis_Data-Mining-Project/blob/master/Presentation/Slide12.jpeg?raw=true
      )
      
![alt text](https://github.com/SONAMDAWANI/Food.com-Data-Analysis_Data-Mining-Project/blob/master/Presentation/Slide13.jpeg?raw=true
      )
      
![alt text](https://github.com/SONAMDAWANI/Food.com-Data-Analysis_Data-Mining-Project/blob/master/Presentation/Slide14.jpeg?raw=true
      )
      
![alt text](https://github.com/SONAMDAWANI/Food.com-Data-Analysis_Data-Mining-Project/blob/master/Presentation/Slide15.jpeg?raw=true
      )
      

![alt text](https://github.com/SONAMDAWANI/Food.com-Data-Analysis_Data-Mining-Project/blob/master/Presentation/Slide16.jpeg?raw=true
      )
      
![alt text](https://github.com/SONAMDAWANI/Food.com-Data-Analysis_Data-Mining-Project/blob/master/Presentation/Slide17.jpeg?raw=true
      )
      
![alt text](https://github.com/SONAMDAWANI/Food.com-Data-Analysis_Data-Mining-Project/blob/master/Presentation/Slide18.jpeg?raw=true
      )
      
![alt text](https://github.com/SONAMDAWANI/Food.com-Data-Analysis_Data-Mining-Project/blob/master/Presentation/Slide19.jpeg?raw=true
      )
      
![alt text](https://github.com/SONAMDAWANI/Food.com-Data-Analysis_Data-Mining-Project/blob/master/Presentation/Slide20.jpeg?raw=true
      )
      

![alt text](https://github.com/SONAMDAWANI/Food.com-Data-Analysis_Data-Mining-Project/blob/master/Presentation/Slide21.jpeg?raw=true
      )
      
![alt text](https://github.com/SONAMDAWANI/Food.com-Data-Analysis_Data-Mining-Project/blob/master/Presentation/Slide22.jpeg?raw=true
      )
      
![alt text](https://github.com/SONAMDAWANI/Food.com-Data-Analysis_Data-Mining-Project/blob/master/Presentation/Slide23.jpeg?raw=true
      )
      
![alt text](https://github.com/SONAMDAWANI/Food.com-Data-Analysis_Data-Mining-Project/blob/master/Presentation/Slide24.jpeg?raw=true
      )
      
![alt text](https://github.com/SONAMDAWANI/Food.com-Data-Analysis_Data-Mining-Project/blob/master/Presentation/Slide25.jpeg?raw=true
      )
      

Please check the below notebook for details:
https://github.com/SONAMDAWANI/Food-and-Recipies-Data-Analysis_Data-Mining-Project/blob/master/DM_Project_Code.ipynb
