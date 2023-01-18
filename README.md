# BrG7_Team4

(-with the term 'hole' or 'holes' i refer to a period of few years where we had lack of data)

Final project for the Data science team. We were given a dataset containing (Country Name, Country Code,	Indicator Name,	Indicator Code,	Attribute and years 1800-2020 as columns) we had freedom to choose what we want to set as our goal and what we can show as a plot of the whole dataset and just be creative with it in some way.
Simply put this dataset contained 'Gross Government Debt', 'Gross Domestic Product' and 'Debt to GDP Ratio' for 193 countries throughout the period from 1800-2020 year.
First we decided to transform the dataset to be easier to work with, than we made some visuals and shown the characteristics of the dataset in which we saw that there are many 'holes' and we set as our goal to compare the European countries with US as financially one of the most powerful countries even to this day.
After we set our goal we than saw from the visuals which period has tha minimum 'holes' for all the countries we chose and we chose the period between 1980-2020 but there were still holes so we made a function to calculate what was possible to be calculated and for the rest we used mean 
We made a for loop which will train models with different specs on the years 1980-2015 and we used the last 5 years to value the best model and we took for each country the best model and we predicted 'Debt to GDP Ratio' for the next 5 yeares (2021-2025) 
