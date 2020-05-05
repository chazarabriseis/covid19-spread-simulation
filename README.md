# covid19-spread-simulation
Jupyter notebook to look at covid19 data and a model of the spread


The data is clone from the github repository of the Johns Hopkins University: https://github.com/datasets/covid-19
The data visualization notebook allows to look at the confirmed, recovered, sick and death cases in all countries listed in the datbase.
The datbase has updated number for every day starting in January 2020. 
Instead of showing the numbers of cases the percentage of the population is us to show population percentage.
The source of the population data: https://datahub.io/JohnSnowLabs/population-figures-by-country#resource-population-figures-by-country-csv

The jupyter notebook with the simulation is using the modsim package from source: https://github.com/AllenDowney/ModSimPy
The simulations is trying to simulate the data from Germany, but it can be adjusted to any other country.
The simulation takes into acount that action can be taken, like social distancing, wearing masks. 
This will alter the probabilty of infection over time.
