# traffic-congestion-prediction-multiple-regression-techniques
#### Predicting traffic congestion at 4 major US cities’ intersections

With the presence of more vehicles in a city and the increasing rate of urban modernization, the state of congestion in roads has become a pressing issue. A lot of measures have been taken to regulate the traffic flow with the help of technology. With the advancement in Machine learning, the traffic congestion systems have become more efficient. Evaluation of various traffic parameters help us to identify the areas of congestion. In this project, the time stopped at a junction and the distance at which the vehicle first stops with respect to the intersection are the two main targets which will be predicted to understand the traffic density. Various regression techniques in Machine Learning are implemented for traffic congestion prediction in the major intersections of Atlanta, Boston, Chicago, and Philadelphia. The results obtained from the models are compared to provide the model with the best performance. Tree based algorithms such as Random Forest work well on our dataset due to their ability to handle large datasets, missing values, and high carinality categorical features.

#### The methodolgy followed is - 
Data Preprocessing <br />
Handling missing data and categorical variables <br />
Feature Selection and Feature Extraction <br />
Exploratory Data Analysis <br />
Data Modelling and Validation <br />

#### The results obtained are documented below - 
![Result 1](https://user-images.githubusercontent.com/94414506/227138601-28023bad-9c94-425f-a5e4-f87e0e00920f.png) <br />
Fig 1: Results from Random XGBoost

   ![Result 2](https://user-images.githubusercontent.com/94414506/227138665-c21081a7-e3e7-49c3-9a72-0c634af86442.png) <br />
   Fig 2: Results from Random Forest


#### Conclusion - 
We were predicting traffic congestion using two main targets, total time stopped and distance to first stop. Various regression techniques were applied and the results were compared based on the performance of the models on both the train and test sets. The metrics used to measure the performance are Mean Squared Error and R Squared scores. From the results obtained, we found that Random forest provides the best results in predicting traffic congestion and feature importance done using Random forest helped us in identifying the factors which affect traffic congestion the most. By forecasting traffic hotspots, we can help in regulation of traffic lights to make the traffic flow easier for the commuters.
