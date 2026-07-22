# Data
The original dataset used for this project cannot be redistributed due to data-access restrictions.

The repository therefore provides small synthetic datasets with the same variable structure as the modelling data. These files are intended only to demonstrate the complete modelling workflow.

This dataset comes from R package CASdatasets - freMTPL. 

## Variables

This datasets contains 10 columns.

- 'PolicyID': The policy ID (used to link with the claims dataset).
- 'Power': The power of the car (ordered categorical).
- 'CarAge': The vehicle age, in years.
- 'DriverAge': The driver age, in years (in France, people can drive a car at 18).
- 'Brand': The car brand divided in the following groups: A- Renaut Nissan and Citroen, B- Volkswagen, Audi, Skoda and Seat, C- Opel, General Motors and Ford, D- Fiat, E- Mercedes Chrysler and BMW, F- Japanese (except Nissan) and Korean, G- other.
- 'Gas': The car gas, Diesel or regular.
- 'Region': The policy region in France (based on the 1970-2015 classification).
- 'Density': The density of inhabitants (number of inhabitants per km2) in the city the driver of the car lives in.
- 'ClaimNb': Number of claims during the exposure period.
- 'ClaimAmount': The cost of the claim, seen as at a recent date.

All policy exposures are assumed to equal 1 in this project.
