## XGBoost model

This project used XGBoost model for prediction of sale price and then the result was compared with other algorithms such as Random Forest and Decision Tree.

## Data fields
Here's a brief version of what you'll find in the data description file.
<ul>
</li>SalePrice - the property's sale price in dollars. This is the target variable that you're trying to predict.</li>
</li>MSSubClass: The building class</li>
</li>MSZoning: The general zoning classification</li>
</li>LotFrontage: Linear feet of street connected to property</li>
</li>LotArea: Lot size in square feet</li>
</li>Street: Type of road access</li>
</li>Alley: Type of alley access</li>
</li>LotShape: General shape of property</li>
</li>LandContour: Flatness of the property</li>
</li>Utilities: Type of utilities available</li>
</li>LotConfig: Lot configuration</li>
</li>LandSlope: Slope of property</li>
</li>Neighborhood: Physical locations within Ames city limits</li>
</li>Condition1: Proximity to main road or railroad</li>
</li>Condition2: Proximity to main road or railroad (if a second is present)</li>
</li>BldgType: Type of dwelling</li>
</li>HouseStyle: Style of dwelling</li>
</li>OverallQual: Overall material and finish quality</li>
</li>OverallCond: Overall condition rating</li>
</li>YearBuilt: Original construction date</li>
</li>YearRemodAdd: Remodel date</li>
</li>RoofStyle: Type of roof</li>
</li>RoofMatl: Roof material</li>
</li>Exterior1st: Exterior covering on house</li>
</li>Exterior2nd: Exterior covering on house (if more than one material)</li>
</li>MasVnrType: Masonry veneer type</li>
</li>MasVnrArea: Masonry veneer area in square feet</li>
</li>ExterQual: Exterior material quality</li>
</li>ExterCond: Present condition of the material on the exterior</li>
</li>Foundation: Type of foundation</li>
</li>BsmtQual: Height of the basement</li>
</li>BsmtCond: General condition of the basement</li>
</li>BsmtExposure: Walkout or garden level basement walls</li>
</li>BsmtFinType1: Quality of basement finished area</li>
</li>BsmtFinSF1: Type 1 finished square feet</li>
</li>BsmtFinType2: Quality of second finished area (if present)</li>
</li>BsmtFinSF2: Type 2 finished square feet</li>
</li>BsmtUnfSF: Unfinished square feet of basement area</li>
</li>TotalBsmtSF: Total square feet of basement area</li>
</li>Heating: Type of heating</li>
</li>HeatingQC: Heating quality and condition</li>
</li>CentralAir: Central air conditioning</li>
</li>Electrical: Electrical system</li>
</li>1stFlrSF: First Floor square feet</li>
</li>2ndFlrSF: Second floor square feet</li>
</li>LowQualFinSF: Low quality finished square feet (all floors)</li>
</li>GrLivArea: Above grade (ground) living area square feet</li>
</li>BsmtFullBath: Basement full bathrooms</li>
</li>BsmtHalfBath: Basement half bathrooms</li>
</li>FullBath: Full bathrooms above grade</li>
</li>HalfBath: Half baths above grade</li>
</li>Bedroom: Number of bedrooms above basement level</li>
</li>Kitchen: Number of kitchens</li>
</li>KitchenQual: Kitchen quality</li>
</li>TotRmsAbvGrd: Total rooms above grade (does not include bathrooms)</li>
</li>Functional: Home functionality rating</li>
</li>Fireplaces: Number of fireplaces</li>
</li>FireplaceQu: Fireplace quality</li>
</li>GarageType: Garage location</li>
</li>GarageYrBlt: Year garage was built</li>
</li>GarageFinish: Interior finish of the garage</li>
</li>GarageCars: Size of garage in car capacity</li>
</li>GarageArea: Size of garage in square feet</li>
</li>GarageQual: Garage quality</li>
</li>GarageCond: Garage condition</li>
</li>PavedDrive: Paved driveway</li>
</li>WoodDeckSF: Wood deck area in square feet</li>
</li>OpenPorchSF: Open porch area in square feet</li>
</li>EnclosedPorch: Enclosed porch area in square feet</li>
</li>3SsnPorch: Three season porch area in square feet</li>
</li>ScreenPorch: Screen porch area in square feet</li>
</li>PoolArea: Pool area in square feet</li>
</li>PoolQC: Pool quality</li>
</li>Fence: Fence quality</li>
</li>MiscFeature: Miscellaneous feature not covered in other categories</li>
</li>MiscVal: $Value of miscellaneous feature</li>
</li>MoSold: Month Sold</li>
</li>YrSold: Year Sold</li>
</li>SaleType: Type of sale</li>
</li>SaleCondition: Condition of sale</li>
<ul>

## Dataset

  The dataset is available in Kaggle website: https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data
