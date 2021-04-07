# House-Price-Prediction
I set out to use some regression models to predict housing prices in Iowa. I will be highlighting how I went about it, what worked for me, what didn’t and what I learnt in that process. Then we will find which model works the best.

![1_us8OB_BbS2BCHYQY9Qlv0w](https://user-images.githubusercontent.com/17608830/112728184-13f45c00-8f4c-11eb-8dda-d5beafb6c25f.jpeg)

### First what is the problem?
The problem is to build a model that will predict house prices with a high degree of predictive accuracy given the available data. More about it [here](https://www.kaggle.com/c/house-prices-advanced-regression-techniques).\
“With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.”

### Where I got the data
The dataset is the prices and features of residential houses sold from 2006 to 2010 in Ames, Iowa. Obtained from [here](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data).

### Data Description
Here is a data [description file](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data). (data_description.txt)
* SalePrice — the property’s sale price in dollars. This is the target variable that you’re trying to predict.
* LotArea: Lot size in square feet
* Neighborhood: Physical locations within Ames city limits
* OverallQual: Overall material and finish quality
* OverallCond: Overall condition rating
* YearBuilt: Original construction date
* TotalBsmtSF: Total square feet of basement area
* GrLivArea: Above grade (ground) living area square feet\
e.t.c

### Environment and tools
jupyter notebook, numpy, pandas, seaborn, matplotlib, scipy and scikit-learn.
