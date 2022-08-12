# DataImputation_GMM_KNN
It can impute the numerical missing values by using the 
mean value from the data using KNN method. In this project in the first step the gaussian mixture 
model is firstly used to simulate the dataset. The estimated parameters from gaussian mixture 
model are used further in the algorithm. After clustering from the gaussian mixture model the K 
nearest mean method is applied to impute the missing values. For every value the distance is 
calculated from the nearest neighbours. The missing value is calculated by the average of the 
values calculated from neighbours. 
