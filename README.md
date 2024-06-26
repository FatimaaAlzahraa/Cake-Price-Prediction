# Cake-Price-Prediction

## Goal
build a machine learning model that can predict the price of cakes based on their features.

## Dataset
➔ You are provided with a dataset in CSV format with the following columns:

◆ Sold_On: The day on which the cake has been sold (e.g., Saturday, Sunday, Monday, Tuesday, Wednesday, Thursday, Friday).

◆ Size: The size of the cake (e.g., small, medium, large).

◆ Ingredients_Cost: The cost of the ingredients used to make the cake.

◆ Time_Taken: The time taken to make the cake (in hours).

◆ Price: The price of the cake.

◆ Amount: The amount of similar cakes sold in the same order (Price and all other parameters are for one cake, not the whole order).

◆ Gender: The gender of person ordering the cake(s).

STEPS:

◆ first i read data set

◆ show the columns information (columns names and data types )

◆ see if there's null values in rows

◆  Used pandas to examine the histograms of the dataset columns (numerical)

◆  used One-hot encoding to Manipulating category features to convert to numerical columns ( beacuse can't use categories columns in machine models ) then after encoding features selection by remove category columns 

◆ then i split datd features and label and split test and train 

◆ used regression models (linear regression and randomforest Regressions ) 

◆ show accurcy train , accurcy Model Evaluation ( score between y_actual and y_pred) used mean_squared_error and r2_score 

◆ in linear regressions show Coefficients and Intercept and used StandardScaler to improve the performance and convergence of various machine learning algorithms
