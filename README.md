**Title**: House Sales Prediction Analysis 


**Project Scenario**: You are tasked with determining the market price of a house given a set of features. You will analyze and predict housing prices using attributes or features such as square footage, number of bedrooms, number of floors, and so on.

**Dataset:** The dataset contains house sale prices for King County, which includes Seattle. It includes homes sold between May 2014 and May 2015. It was taken from here. It was also slightly modified for the purposes of this course. 

**Scope of Functionality or Questions to Answer:** 
1. Display the data types of each column using the function dtypes
2. Drop the columns "id" and "Unnamed: 0" from axis 1 using the method drop(), then use the method describe() to obtain a statistical summary of the data.
3. Use the method value_counts to count the number of houses with unique floor values, use the method .to_frame() to convert it to a dataframe.
4. Use the function boxplot in the seaborn library to determine whether houses with a waterfront view or without a waterfront view have more price outliers
5. Use the function regplot in the seaborn library to determine if the feature sqft_above is negatively or positively correlated with price.
6. Fit a linear regression model to predict the 'price' using the feature 'sqft_living' then calculate the R^2.
7. Fit a linear regression model to predict the 'price' using the list of features:
8. Use the list to create a pipeline object to predict the 'price', fit the object using the features in the list features, and calculate the R^2.
9. Create and fit a Ridge regression object using the training data, set the regularization parameter to 0.1, and calculate the R^2 using the test data.
10. Perform a second order polynomial transform on both the training data and testing data. Create and fit a Ridge regression object using the training data, set the regularisation parameter to 0.1, and calculate the R^2 utilising the test data provided.

**Click to view completed Jupyter Nbviewer ipynb:** 
1. [Importing Datasets ipynb](https://nbviewer.jupyter.org/github/topgyaltsering/House-sales-prediction/blob/main/intro.ipynb)
2. [Data Wrangling ipynb](https://nbviewer.jupyter.org/github/topgyaltsering/House-sales-prediction/blob/main/Data%20Wrangling.ipynb)
3. [Exploratory Data Analysis (EDA) ipynb](https://nbviewer.jupyter.org/github/topgyaltsering/House-sales-prediction/blob/main/EDA.ipynb)
4. [Model Development ipynb](https://nbviewer.jupyter.org/github/topgyaltsering/House-sales-prediction/blob/main/model%20dev.ipynb)
5. [Model Evaluation and Refinement ipynb](https://nbviewer.jupyter.org/github/topgyaltsering/House-sales-prediction/blob/main/model%20evaluation.ipynb)

**Complete Jupyter Lab**:
[Jupyter nbviewer Prediction House_sales ipynb](https://nbviewer.jupyter.org/github/topgyaltsering/House-sales-prediction/blob/main/House_sales.ipynb)


## Resources referred:
- [Exploratory Data Analysis](https://nbviewer.jupyter.org/github/Tanu-N-Prabhu/Python/blob/master/Exploratory_data_Analysis.ipynb)
- [Data Integration / Cleansing at a smaller scale](https://towardsdatascience.com/data-cleaning-with-python-using-pandas-library-c6f4a68ea8eb)

