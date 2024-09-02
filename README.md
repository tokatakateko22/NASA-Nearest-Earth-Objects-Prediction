# NASA-Nearest-Earth-Objects-Prediction
machine learning model that can accurately predict whether a NEO is hazardous or not.

There are many dangerous bodies in space, one of them is N.E.O. - "Nearest Earth Objects". Some such bodies really pose a danger to the planet Earth, NASA classifies them as "is_hazardous". This dataset contains ALL NASA observations of similar objects from 1910 to 2024!!!

There are 338,199 records of N.E.O. in the Dataset!

Try to predict "is_hazardous" as accurately as possible! (otherwise we will not be ready for an asteroid attack)

# The Main Steps of the process are :
  1- Loading and exploring the data 
  
  2- Exploratory Data Analysis
  
  3- Data Preprocessing 
  
  4- Splitting the data into train and test 
  
  5- Building the model 
  
  6- Train the model and explore the results and accuracy 

---------------------------------------------------------------------------------------------------------------------------------------------------

The main notices that is found while exploring the data that there existed 2-highly correlated feature so I had to drop one of them 

I also dropped the categorical columns which will not be affecting the model at all (useless)

Encoded the target variable into 0,1 for the model to be able to read it 

Since the data is not large enough the accuracy came back high 91% and the ROC score 94% , there may exist an overfitting 

Take a deep look in the code and hope it will be good and informative
