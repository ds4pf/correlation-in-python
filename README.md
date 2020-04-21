# correlation-in-python
This code shows how to create a correlation matrix and correlation heatmap in python

There are three notebooks:
1. correlation-in-python.ipynb
 The basic python notebook that uses the same input data as the corresponding R example
2. correlation-ip-yfin.ipynb
 The correlation in python that uses the yfinance API as data source
3. correlation-ip-fonds.ipynb
 The correlation in python example that uses data from ariva. I added some mutual funds here. To retrieve the data execute the scripts from the data-funds directory:
 - getQuotes.sh to download the data as [wkn]_historic.csv. You can use min_date and max_date to retrieve a certain period of data (e.g. `getQuotes.sh 19.09.2019 03.04.2020`)
 - revertFiles.sh to convert the data in usable format (date and close from old to new)  
   
 Before using these scripts remember to delete all *.csv from the data-funds directory.

