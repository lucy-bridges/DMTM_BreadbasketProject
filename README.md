# DMTM_BreadbasketProject
## Team Members
Lucy Bridges
Megan Morano
Wyatt Smith
Chris Willman
## Executive Summary

The BreadBasket dataset is a list of transactions from a grocery store of some kind. Our team decided to use the arules and arulesViz libraries in RStudio to conduct an analysis of this dataset. We started off with some basic data exploration. We looked at the head and tail of the dataset, sorted by time, to look at some of the items bought in the morning and some of the items bought at night.This also served as a reference-point for attribute names and types. Then, the main data file was split into 3 additional files: MorningData, AfternoonData, and EveningData. These would later be used to conduct arules analysis of those individual time frames.

After some exploration of the new datasets, arules analysis began. First, we had to convert the data to transaction datasets. Then we made item frequency plots of all 4 datasets. After running each set through the apriori() function, we were able to inspect the generated rules by lift to see which rules were the most likely to occur. Finally, we used arulesViz to create network diagrams of the rules and look for clusters of items along with the plot() function to create scatterplots of confidence against support. 

We conlcuded that, while there were some interesting obvservations to be made, the data did not contain much information of practical use. This could be wrong, as we are fairly inexperienced association rule miners. 
