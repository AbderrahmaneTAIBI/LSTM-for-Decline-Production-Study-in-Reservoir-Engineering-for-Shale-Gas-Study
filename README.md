# LSTM for Decline Production Study in Reservoir Engineering for Shale Gas Study
This Jupyter Notebook contains the code for applying LSTM (Long Short-Term Memory) for decline production study in reservoir engineering for shale gas study applied to the dataset "HS01DataCummulativeNonZeros.csv".

## Libraries and Files
The following libraries are imported for this project:

* numpy
* matplotlib
* pandas
* seaborn
* warnings
* time
* scipy
* statsmodels
* sklearn
* keras

## Dataset
The dataset used for this project is "HS01DataCummulativeNonZeros.csv". This dataset contains data on the gas production of a shale gas well. The "Time (Days)" column contains the number of days since the start of production and the "Gas Volume" column contains the cumulative gas production in millions of cubic feet.

## Data Pre-processing and Feature Engineering
Before constructing the LSTM model, the following data pre-processing and feature engineering needs to be done:

* Normalize the features
* Split into training and test sets
* Convert an array of values into a dataset matrix
* Reshape into X=t and Y=t+1
* Reshape input to be 3D (num_samples, num_timesteps, num_features)

## Exploratory Data Analysis (EDA)
EDA is done using various plots such as time series plot, distribution plot, and Dickey-Fuller test.

## LSTM Model
The LSTM model is constructed using Keras.

## Conclusion
Overall, this project provides a useful method for predicting future production in reservoir engineering for shale gas study using LSTM. It showcases the power of deep learning in the energy industry and the potential for improving operational efficiency and reducing costs.
