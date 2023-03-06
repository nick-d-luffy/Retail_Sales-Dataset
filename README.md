# Retail_Sales-Dataset
Using Recurrent Neural Net to predict the sales for one year into the future.

Ill be testing and training the data using test_size=18.

Ill be scaling the test and train data using MinMaxScaler.

Ill use a TimeseriesGenerator for 12 months using length

Ill create the model and then will use a early stop call back.

Ill create a validation Generator to fit the model.

The losses will be plotted.

I will evaluavte the test data and and perform inverse transformations.

I will rescale the full data and retrain the model again.

I will forecast the data and perform inverse transformation on the forecast data.

I will create a new time stamp and Index it with pandas and join the plots to make predictions 1 year into the future.
