# Dense Neural Network Regression #
*California Housing Data*

This data set contains information about all the block groups in California from the 1990 Census. In this sample a block group on average includes 1425.5 individuals living in a geographically compact area.

The task is to approximate the median house value of each block from the values of the rest of the variables.

It has been obtained from the LIACC repository. The original page where the data set can be found is: http://www.liaad.up.pt/~ltorgo/Regression/DataSets.html.

The Features:
  
housingMedianAge: continuous.  
totalRooms: continuous.  
totalBedrooms: continuous.  
population: continuous.  
households: continuous.  
medianIncome: continuous.  
medianHouseValue: continuous.  

Note: I performed feature scaling using Sklearn's MinMaxScaler()
## CONCLUSION: ##
Obtained RMSE of 97652 after running DNNRegressor model that was trained with 25000 steps. The model had 3 hidden layers with 6 hidden nodes in each layer.
