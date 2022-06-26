Analysis of Global COVID-19 Pandemic Data


Final Project on the Introduction to R Programming for Data Science


An online non-credit course authorized by IBM and offered through Coursera
The project was carried out with R, originally on the IBM Watson Workspace


About the Data
The data is from an HTML Table on a Wikipedia page describing COVID-19 testing statistics  by 172 countries of the world. (I.e 172 rows)


The data can be found at https://en.wikipedia.org/w/index.php?title=Template:COVID-19_testing_by_country


The table variables include:
* Country or region
* Date 
* Tested
* Units
* Confirmed (cases)
* Confirmed / tested, %
* Tested / population, %
* Confirmed / population, %
* Ref.


Further description of the column is found below.




Brief Summary
A function was written and called to pull COVID-19 pandemic data from a Wikipedia page using HTTP request


Covid-19 testing data was extracted from Wikipedia html page
The data was preprocessed and saved as a .csv file
The columns of the dataframe are listed below:
* country - The name of the country
* date - Reported date
* tested - Total tested cases by the reported date
* confirmed - Total confirmed cases by the reported date
* confirmed.tested.ratio - The ratio of confirmed cases to the tested cases
* tested.population.ratio - The ratio of tested cases to the population of the country
* confirmed.population.ratio - The ratio of confirmed cases to the population of the country
Other operations include some quick analyses and comparisons of infection rates among the countries.