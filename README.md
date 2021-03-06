# Housing-Sales-Price-Ames-Iowa
# Collaborative project for MSDS6372-Applied Statistics: Inferenceing and Modeling
### By:
### James Hosker
### Timothy McWilliams
### Leticia Valadez

## SAS (Staistical Analysis Software) was used to complete this project.

## This project provides insight into the home sales in Ames, Iowa from 2006-2010.  We explore several factors that affect the sale prices of homes such as the usual suspects of neighborhood, square footage, year built and not so typical thought of factors such as a full bathroom in basement. Housing sales data for the Ames, Iowa housing market is publicly available at the following URL  Housing Data for Ames Iowa.  The Ames, Iowa Housing dataset was compiled by Dean De Cock of Truman State University[1].  A full description of each data field is given in the “data_description,txt” text file at the referenced URL.  Our team develops a concise model using multiple linear regression techniques for Ames’s housing sale price. The model will help real estate agents, contractors, and prospective buyers gain important insight on the factors that are currently influencing housing sale prices in Ames, Iowa. Our model can be complex due to the substantial number of explanatory variables.  However, our model is narrowed down to the most significant factors to keep the model as simple as possible. This is primarily achieved by using the LASSO variable-selection method.

## We develop a multiple linear regression model based on an observed training data set of 79 explanatory variables and one sales price response variable for the Ames, Iowa housing market.  We then use this model to predict housing sales prices in Ames, Iowa using a different test data set of only explanatory variables.

## This is an observational study and not a control randomized study, since the data was collected on housing sales that occurred in Ames, Iowa from 2006 to 2010. Only correlation between explanatory variables and response variable (SalePrice) can be made and no causal relationship can be made between these variables. First, it is possible these data sets do not include some explanatory variables that more appropriately describe the variation in housing sales prices.  Second, we do not know if the same or different brokers that may have different biases filled out the explanatory information. The data includes all residential sales in Ames, Iowa; however, approximately 100 homes changed ownership multiple times during the 4-year period.  To avoid giving more weight to these 100 homes, only the most recent sales data on these homes were included in the original data sets reduced by Dean De Cock of Truman State University. Any inferences that are made can only apply to the city of Ames and not the whole state of Iowa or any other population.

## References
## [1] Dean De Cock, “Ames, Iowa: Alternative to the Boston Housing Data as an End of Semester Regression Project”, Journal of Statistics Education, Volume 19, Number 3(2011).

## For a more indepth detail on this project download the Final report above.
