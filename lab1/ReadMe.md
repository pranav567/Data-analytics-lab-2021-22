In this experiment, the objective was to perform exploratory data analysis on the given dataset. The dataset for this experiment is about criminal data of the city of Denver between Jan,2012 and Oct,2016. Initially, I have performed basic operations like the total data shape, finding the missing values and the removing them, number of classes and samples available per class. The classes were then converted into numeric representation. Using seaborn library, graphs are plotted of types like histogram, barplot, distribution plot, scatterplot and lineplot. From these graphs some of the inference made were:

from the sactter plot, which shows distribution of crime across denver, most of the crime took place in the central region and the number decreases as it moves to the corners
from the lineplots, one can see how the crimes increased/decreased from Jan,2012 to Oct,2016 and also how it changed on yearly basis
the total number of offenses when viewed on the monthly basis has an uneven distribution but when viewed yearly, it shows increase in cases for 3 years with peak at 2014 and decline in the next 2 years.
from the lineplot between year of incidents and delay in reporting a crime, it is obsereved that the average time(number of days) between an incident occurring and a report being filed decreased.
from the distribution plot for districts in denver, we can see that most of the crimes that took place in each district were of the category 'Burglary'
from the distribution plots, we can see that for incident address, district, precinct and offense code, how the total criminal acts that took place is distributed.
from the histplot between average delay in reporting a crime and offense category, the category 'Larceny' has the highest average delay
the address '745_S_BRYANT_ST' had reported an offense of Burglary, of category 'Burglar_No_Force' located in the district with id '4' and at precinct id '412' on '2015-02-02'. The crime took place on '2014-01-28'
the precinct with id 323 has the highest average delay having a crime reported
the district with id 2 and precinct with id 212 had the highest number of crime reported
neighbourhood - 'elyria-swansea' had reported highest number of criminal offenses
most of the incidents reported had connections to marijuana industry (~800/1253).
'burglary' is most repeated offense, the district with id '3' has seen a lot of cases of burglary while district with id '2' least.