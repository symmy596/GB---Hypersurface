# GB - Hypersurface

##### Author - Adam Symington 
##### Date - 17/07/2018

Quick tool to convert METADISE[1] grain boundary scan results to energy surface plots. The script takes a csv file consisting of configuration energy as a function of x and y surface displacement and outputs an energy surface. 

##### Basic Usage:


	X, Y, Grid = ReadGrid("YourFileName.csv")
	GridPlot(X, Y, Grid)


[1] - G.W. Watson, E.T. Kelsey, N.H. deLeeuw, D.J. Harris, S.C. Parker, J. Chem. Soc., Faraday Trans. 92 (1996) 433–438
