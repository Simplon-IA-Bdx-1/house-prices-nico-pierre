# house-prices-pierrembgit-nicookie

Work on the House Prices Kaggle Challenge

## Prep

### Datavizualisation

Using R to check the datas.

- make a regression first to try to find the most importants features in the set?
- What data do we want to make a prediction on => what is the output?
  - The price of a house
- Shape datas :
  - Number of features, number of lines in each dataset
  - Correlations between features => Corelation matrix
  - libs :
    - summarytools => define the dataset
    - FactoMineR + facto extra => PCA

### Modeling

Using Python to create a ML model for a regression problem.

Sklearn...

## Run

### Data observation

- Looked at the correlations between numeric features and SalesPrices
- about a dozen features are highly correlated with the SalesPrice :
  - OverallQual
  - GrLivArea
  - GarageCars
  - GarageArea
  - TotalBsmtSF
  - X1stFlrSF
  - FullBath
  - TotRmsAbvGrd
  - YearBuilt
  - YearRemodAdd
  - Fireplaces
- OverallQual as a quite normal (gaussian) distribution
- Old houses with high OverallQual make the price go higher
