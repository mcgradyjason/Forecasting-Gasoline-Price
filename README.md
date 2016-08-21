# Forecasting-Gasoline-Price-in-Chicago-Area-Using-Time-Series-Models

#Object
Weekly data were collected of regular gasoline retail price in Chicago area ranging from 12/01/2008 to 11/30/2015, ARIMA, ARMA and VAR models were applied aiming to capture movement of gasoline price.

#Data
Weekly Chicago Regular All Formulations Retail Gasoline Prices were collected from U.S. Energy Information Administration
https://www.eia.gov/dnav/pet/hist/LeafHandler.ashx?n=PET&s=EMM_EPMR_PTE_YORD_DPG&f=W
Crude Oil Prices: West Texas Intermediate (WTI) - Cushing, Oklahoma were collected from U.S. Energy Information Administration
http://www.eia.doe.gov/dnav/pet/TblDefs/pet_pri_spt_tbldef2.asp

#Software
All the analysis work was run on EViews

#Models
(1) ARIMA
(2) ARMA with seasonal dummy variables
(3) VAR with crude oil price

#Performance
(1) ARIMA model has the ability to capture basic direction of gasoline price movement, but low
R2 and forecast plot indicates limited explanatory power with less capability to forecast future gasoline price. 

(2) ARMA model with seasonal dummy variables capture the main trend of gasoline price, it has strong explanatory power and forecasting ability, the drawback of this model is that it consists of too many independent variables, seasonal dummy variables based on 12 months or 4 seasons should be enough to capture seasonality. 

(3) The last model basically uses Crude Oil Price as proxy to indicate gasoline price, but it is not possible for every data to find a perfect proxy like this.
