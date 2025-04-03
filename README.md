The objective of this exercise is to develop and evaluate a model that can be used to predict the rating of an app on google play store provided other relevant data about the app is available

This project uses the afore cleaned google play store data. Mored details can be found https://github.com/papaulj/Comprehensive-Data-Cleaning

The prediction equations is given by Ratings = 1.3726e-07(Rating Count) -1.5339e-09(Installs) -1.5339e-09(Minimum Installs)+1.1676e-08(Maximum Installs) -0.12717(Free)+0.0046(Size)
The above equation further shows that the size of the app is the single biggest determinantg of the average rating of the app by users 

The R-squareed value of 0.0038 reveals that the probability thatr changes in the input variables will bring about changes in the predicted rating is 0.38%.
This confirms that the model created is a poor predictor of the rating that an app will get. This finding is also confirmed from the inability of the scatter plot of predicted and actual rating to fall on a diagonal line.

The result of the mean absolute error further implies that the average of the diference between the predicted rating and the actual rating of the test data is 2.04. 
This value is high when compared to the range of the rating (1 to 5) and further confirms that the developed model has a very low accuracy in determining the rating of an app
