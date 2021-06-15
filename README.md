# Elasticity
Spotprice elasticity of electricity demand and factors that can influence the electricity demand.
Please help!

## Goals
1. Estimate price elasticity of demand through log-log regression to get elasticity
2. Estimate if there another variables that can effect demand.

## DATA
You can find a sample dataset in this repository, based on a real sales.
Similar to typical time serie aktie data, but with both price value and demand values.
The set of independent variables will be regressed to see if they causes effect on the demand variable. 
It is a monthly data from 2013-2020 which have 96 observations.
date -> monthly sequence from 2013-2020
dem -> the avarage quantity of mWh that was sold
price -> the avarage price of mWh
pop -> population
gdpc -> avarage income per capita
temp -> avarage temperature
exchange -> avarage import/export in kWh 
sekeur -> exchange rates between SEK and EUR
season -> is a seasonal dummyvariable which has value 1 if it's October - March, otherwise 0

## Overview
The main aim of the pricing studies is to learn about past impact of the price on sales and try to adjust future actions.  The consumer's sensitivity to price changes can be measured by the coefficient of price elasticity. Elasticity measures how much the quantity demanded for one good will fall if the price for one good will increase by 1% and the change in the price and quantity will measure the elasticity.

