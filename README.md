# House-Price-Prediction-Model
![image](https://user-images.githubusercontent.com/98249716/201017580-fe1d52bf-fe32-4548-889a-3705bf494209.png)

### Developed Machine Learning model to predict house prices based on 81 initial features which were then sorted on the basis of problem statement.
## Project Description
#### Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this  dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

#### With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this dataset challenges you to predict the final price of each home.
## Procedure Followed
#### Data is first cleaned by performing exploratory data analysis in which Nan values and wrong formats in features are removed to perform adequate operations. The cleaned data is then checked for outliers which on identification are removed to increase accuracy of the model. One hot encoding is then performed for categorical features.It refers to converting the labels into a numeric form so as to convert them into the machine-readable form. Machine learning algorithms can then decide in a better way how those labels must be operated. It is an important pre-processing step for the structured dataset in supervised learning.
#### Then we start building our model initaing with splitting data through train test split which is then normalized using StandardScaler. We are using ElasticNet Regularisation method to fit in our data. The best parameters for model are found using GridSearchCV . The model is now ready to be applied for any number of data values for which the model will be predicting house-price . 
