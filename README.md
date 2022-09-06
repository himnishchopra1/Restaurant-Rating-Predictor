# Restaurant-Rating-Predictor
An analysis of the dataset follwed up by a visualization of some of my findings. Then using the data I made a model to predict restuarnt rating

Link to dataset:
https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants?resource=downloa

Skills Demonstrated:
- Pandas
- Numpy
- Matplotlib
- Pyplot
- Seaborn
- Linear Regression
- Logistic Regression
- Extra-Trees Regression
- Random Forest Regression

Methods Used:
- Exploratory Data Analysis
- Data Visualization
- Data Cleaning, Feature Engineering
- Model Building

#### Problem:
The aim of this project was to explore the different features of the dataset in order to determine the different trends and see explore the characteristics of Bangalores highest rated restaurants. This imformation would then be used to produce a machine learning model that can predict the rating a restaurant would have if they enter information about their restaurant such as the price of a meal, restaurant type, location, and the menu items availible.


#### Results:
These are some interesting insights found from exploring this data that restaurant owners can consider when thinking about how they should run their restaurant.
![image](https://user-images.githubusercontent.com/91419941/188505531-193bafed-ef7f-4416-93c7-f13ec270902e.png)

Restuaurant owners can consider this distribution of the cost of meals across the restaurants of Bangalore when deciding what they should charge for their own meals.

![image](https://user-images.githubusercontent.com/91419941/188505979-5a65999a-bae4-4398-8bf3-1e3ead19f645.png)

Restaurant owners can consider these dishes to add to their manu as these are the most popular dishes in Bangalore.

#### Model Evaluation:
The Coefficient of Determination-R2 score was used to evaluate the models built in this project. This was the preferred method of evalution because it is the amount of the variation in the output dependent attribute which is predictable from the input independent variables. This is better as it can be observed what restuarants characteristics have the biggest impact on restauarnt rating which changes can be implemented to existing or new restaurants to ensure a higher restuauarant rating.

The Extra-Trees Regressor resulted in a 92.6 % R2 score meaning 92.6 % of the variability of the target can be explained by the model.

Based on the analysis and model it was determined that the most important features that a reatuarant must consider when they want to maximize reataurant rating is the cost of dining for two people, the dishes offered, and location.












