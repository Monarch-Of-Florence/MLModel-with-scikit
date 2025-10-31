imported pandas and scikit learn, rest were unnecessary but nvmm that
so I just assign the csv dataset to a pandas dataframe, label the input and output, then split the dataset into training and testing
ofc had to standardize since this is a linear regression model
made the model and trained it with the data, using all the colums except price as input to predict price. Comparing with metrics like mae, mse and r2 score, the results werent impressive but made me happy
used the accuracy metric initially, then learned it doesnt work here. 
