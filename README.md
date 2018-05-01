#GB---Hypersurface

Quick tool to deal with METADISE[1] GB scan results. The script takes a csv file as an input that is set out 
with displacements as the x and y grid and energies as the grid. 

  dx dx dx dx dx dx dx dx dx dx 

dy e  e  e  e  e  e  e  e  e  e 

dy e  e  e  e  e  e  e  e  e  e 

dy e  e  e  e  e  e  e  e  e  e 

dy e  e  e  e  e  e  e  e  e  e 

dy e  e  e  e  e  e  e  e  e  e

dy e  e  e  e  e  e  e  e  e  e


This script consists of two functions;
ReadGrid - Reads the CSV file, expects a file name as an arguement and returns the X displacements, Y displacement and energy grid. 
	   X, Y, Grid = ReadGrid("YourFileName.csv")
GridPlot - Plots the GB energy surface. Expects the X and Y displacements as well as the energy grid. 
	   GridPlot(X, Y, Grid)

[1] - G.W. Watson, E.T. Kelsey, N.H. deLeeuw, D.J. Harris, S.C. Parker, J. Chem. Soc., Faraday Trans. 92 (1996) 433–438
