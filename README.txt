Plugins-
Software: Terminal (.sh files run .ipynb files)

Environment: conda 4.10.1, python 3.8.8



Dependencies-
Python Libraries: pandas 1.2.4, numpy 1.20.1, matplotlib 3.3.4, scikit learn 0.24.1



Programs-


.sh files:

g5.sh
Top-level script that runs jupyter notebook file as
jupyter nbconvert --to notebook --execute g5-source-code.ipynb


Jupyter notebook files:

g5-source-code.ipynb

Input:	All the datafiles are kept in ‘Data sets’ directory. ‘Data sets’ directory contains following four sub-directories:
	Electricity consumed by EVs: It contains ‘EV_Electricity_consumption.xlsx’ data file.
	Electricity price in india: It contains ‘electricity-price-in-india.xlsx’ data file.
	Oil Data: It contains, 
		    Data for Crude and Products Historical - Quantity.csv
		    Oil import 2011-12.csv
		    Oil import 2012-13.csv
		    Oil import 2013-14.csv
		    Oil import 2014-15.csv
		    Oil import 2015-16.csv
		    Oil import 2016-17.csv
		    Oil import 2017-18.csv
		    Oil import 2018-19.csv
		    Oil import 2019-20.csv
		    Oil import 2020-21.csv
		    consumption-of-diesel-and-petrol-in-india.csv
		    oil_prices_modified.csv
	VehicleDataSet: It contains 70 excel datafiles monthwise from JAN 2016 to OCT 2021.

Output: 'Study impact of electric vehicles on Indian economy (production).csv' and few graph jpg are generated in 'Code/output' directory.


How to run:
In order to run this project, run below mentioned command from the terminal in Code directory-
bash g5.sh


