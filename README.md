# scb
A little project I did in exploration, analysis, and structuring of data on political polls from Statistics Sweden (SCB)

The code pulls JSON data from Statistics Sweden, prepares it, plots it, performs a VAR analysis, and finally adds the data to an SQL table. 

Dependencies: json, urllib, codecs, matplotlib, numpy, statsmodels, pandas, MySQLdb

Plots of the data and a five-steps forecast from a VAR(2) model are included. 
