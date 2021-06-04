# bwb-Battle-of-the-Neighborhoods-w4-1


Capstone-Project---The-Battle-of-Neighborhoods








1A) Background Discussion

Toronto is the capital city of the Canadian province of Ontario. It is the most populous city in Canada. Toronto is an international center for business and finance. It's the financial and industrial center with a high concentration of banks and brokerage firms in the Financial District. 

In 2016 (last census), Toronto's city proper had a population of 2,731,571; the urban area had a population of 5,429,524; the census metropolitan area had a population of 5,928,040; and the Greater Toronto Area metropolitan area had a population of 6,417,516. 

The city's foreign-born persons made up 47% of the population. No single nationality or culture dominates Toronto's immigrant population, placing it among the most diverse cities in the world. In 2016, the three most commonly reported ethnic origins overall were Chinese (12.5%), English (12.3%) and Canadian (12.0%).

Toronto historically has a low crime rate making it one of the safest major cities in North America. In 2007, the homicide rate for Toronto was 3.3 per 100,000 people, compared with Atlanta (19.7), Boston (10.3), Los Angeles (10.0), New York City (6.3), Vancouver (3.1), and Montreal (2.6). Toronto's robbery rate also ranks low, with 207.1 robberies per 100,000 people, compared with Los Angeles (348.5), Vancouver (266.2), New York City (265.9), and Montreal (235.3).

This demographic background makes Toronto an attractive destination for potential business investment.

1B) Business Problem to be Analyzed


This analysis of Toronto is from the perspective of a potential investor who is interested in opening one or more restaurants. 

In particular, this investor is looking at investing and opening fast food restaurants and/or pizza restaurants. In this case 'fast food restaurants' refer to the well-known national brands (eg Arby's, Mcdonalds, Burger King, Subway, Wendy's, etc.) These franchises have international brand recognition as well as established business plans, logistic support, and pricing. Pizza restaurants are a special case of 'fast food' and require a different level of investment and logistics than the national brands (although Papa Johns, Pizza Hut, and Dominos could be investment options.

Determining the potential location of a restaurant is one of the most important factors affecting its future success or a failure. 

So our project will attempt to answer the question: “Where should the investor open a fast food franchise and/or a pizza place?”. 

1C) Problem Statement

What are the best locations for fast food franchises and/or pizza places in Toronto (specifically postal codes starting with 'M')?







2A) Data

In order to answer the above questions, data is collected on Toronto neighborhoods/boroughs including: postal codes, neighborhood name, latitude, longitude, population, population density, income, number of fast food restaurants, and number of pizza restaurants. 

All of this data is compiled and sorted by postal code.

Data has been collected from the FourSquare API utilized via the Request library in Python. 
Additional data has been collected from cybo.com, wikipedia.com, and www150.statcan.gc.ca .

2B) Methodology

i) Data will be compiled by postal code in Toronto. (Toronto 3-character postal codes start with the letter 'M'.)

ii) The data will be collected using the FourSquare API, BeautifulSoup, as well as manually from other websites (see above). 

Iii) The data is then inspected, cleaned and processed into a dataframe.

iv) Data will be sorted based on rankings.

v) Additionally, the data be will be visually analyzed using graphing from Python libraries.

vi) Based on this analysis a number of locations will be recommended.

