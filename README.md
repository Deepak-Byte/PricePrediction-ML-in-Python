# PricePrediction-ML-in-Python
Using of machine learning, build model to predict price of stocks
Download Bank Nifty data in .CSV format from NSE site which contain data from 1 January 2019 to 17 February 2023.\
File contain 7 column namely Date, Open price, Close Price, High (Price of day highest), Low(Price of day lowest), Adjest CLose price and Volume.
For predicting price used only Close price.

Used Numpy, Pandas, Matplotlib and SKLearn library.

Numpy used for handling data in array for easy operation on numbers.
Pandas used for file handling, data cleaning, data visulization.
Matplotlib used for various chart plotting , analyzing data or data visualization.
SKLearn library used for building ML model, train test spliting.

Step wise complete project describtion,
Step 1- Creating main in program and trasported data into program using pandas library.

Step 2- Checking null data and removing it.

Step 3- Ploted chart of number of days vs close price.

Step 4- Make new data frame of close price and then created feature data frame and target data frame.

Step 5- Preapared train and test set data using SKLearn library.

Step 6- Preapared ML model, used two different model for more perfection namely TreeRegression and LinearRegression.

Step 7- Train our model using x-train and x-test data set.

Step 8- Then ploted our predicted value from our trained data set using both model and analysing the data and cheking different model accuracy predction.



In my case Linear model predicted more accurate result as compare to Tree model.
All file and chart are present to this git reposatory.
