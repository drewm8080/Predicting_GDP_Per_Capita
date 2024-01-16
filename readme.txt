First make sure any packages are installed that need to be (scikit learn, pandas etc), which the import statements are in the first few lines of code.


There are two files: analysis--static.py and scrapper--stactic.py

analysis--static.py takes in an csv. This single csv (full_dataset.csv) is all the cleaned data from the scrapper--stactic.py

You can run analysis--static.py by putting the following into terminal:
python analysis--static.py ./full_dataset.csv

This will return the following items (in this order):

1. The dataframe head
2. Plotting GDP per Capita in the United States timeseries plot
3. Printed results from the Random Forest Prediction
4. Feature importance graph for the Random Forest
5. Plotting y-test and y-predicted graph for random forest 
6. A single tree from the random forest visualization
7. Normalized data, dataframe head
8. Comparing the Normalized Data of the Best Preforming Features plot
9. Normalized data, GDP Per Capita vs Stocks

The next file is the scrapper--stactic.py. This takes in all the raw data and then returns the single cleaned large dataframe that contains all the data (full_dataset.csv). This  runs using the following command line code:
python scrapper--stactic.py ./gdp_per_capita.html ./unemployment.json ./Rgdp.json ./PCE.json ./exports_imports.json ./stock_prices
