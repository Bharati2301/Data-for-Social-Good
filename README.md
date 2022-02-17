# Crop Yield Prediction
## INTRODUCTION
* Agriculture is the key activity of human being since it provides basic needs such as food, clothing, and shelter. In the state of Telangana, India throughout the year there 27 important crops that are grown, out of which our project focuses on Maize, Groundnut and Bengal Gram. It has been observed over the years that out of these three, Maize has the highest yield. 
* There are various factors which affect the crop yield, such as soil fertility, availability of water, temperature, rainfall etc. When we compare the total rainfall with the total yield for each of the three crops, it is evident that there is correlation between rainfall and yield for Maize. But correlation doesn’t imply causation, so to predict the yield based on these factors we have used various Machine Learning Techniques.

## MODEL
* Linear Regression: MAE: 996.524 <br>
* XGBoost: Best Params: 'learning_rate': 0.01, 'max_depth': 6, 'n_estimators': 500, 'n_jobs': 3<br>
(1)	Learning rate shrinks the contribution of each tree by learning_rate<br>
(2)	The number of boosting stages to perform. Large number usually results in better performance (epochs)<br>
(3)	The maximum depth limits the number of nodes in the tree<br>
(4)	n_jobs is the number of parallel threads used to run xgboost. On larger datasets where runtime is a consideration, you can use parallelism to build your models faster

* MAE: 449.467

CHECK UNDERFITTING:
* Training set score: 194.29075506663642
* Test set score: 449.4672498703003

## POSTER
![Poster_page-0001](https://user-images.githubusercontent.com/71218441/154459563-2f84aec7-e4e0-4559-a0c6-a4482aadfdc9.jpg)


## FUTURE SCOPE	
* Here we had taken into consideration only two factors i.e., the temperature and rainfall of the districts. There are other factors such as the fertility and type of soil present in the area which would affect the crop yield. On proper analysis we can help find the soil type and fertilizers which can be helpful in maximizing and predicting the crop yield. P.C.A and many Deep Learning techniques can be used on images of the field and crop to detect if they are infected by any disease or the presence of weed, which also affects the quality of the crop, and can be separated from the healthy crops at the earliest possible.
