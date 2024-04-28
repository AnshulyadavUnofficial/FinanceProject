# FinanceProject
A julia project that creates a portfolio to match an index. Needs Mosek licence to run. Mosek is freely available for researchers and students on their website: https://www.mosek.com/.

The optimization script takes in a csv file similar to the one provided in Data folder. The script then creates a allocations file that is stored in the Results/CapitalizationAndStockPrice folder. 
To compare the allocation files across time, use the second part of the script that creates files in the Results/Comparative folder that shows the differential stock allocation.
