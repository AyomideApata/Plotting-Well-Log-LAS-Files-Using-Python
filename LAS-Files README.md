# Plotting-Well-Log-LAS-CSV Files-Using-Python
Plotting Well Log Using Python
Log ASCII Standard (LAS) files is an Oil & Gas (Energy) industry formatted file use for storing and transferring well log data.
This LAS file has data contained which is used to analyze and understand the subsurface, as well as identify potential hydrocarbon reserves.

Importing the Libraries
The first step using the libraries: pandas, matplotlib, seaborn, os, and lasio.
Pandas, welly and lasio will be used to load and store our data. 
whereas matplotlib will be used in visualizing the contents of the wells log data.


Track 1
•	The Gamma ray curve has a green curve and axis ranges from 0 to 150; major gridlines every 75 API; minor gridlines every 25 API.
•	The caliper curve has a red curve. 

Track 2: 
•	Resistivity Curve (Deep & Medium)
•	Major gridlines every log cycle; minor gridlines for minor log cycles 
•	Range from 0.2 to 2000 

Track 3 
•	Neutron and Density porosity curves 
•	Axis ranges from 0.3 to -0.1; major gridlines every 0.1; minor grid lines every 0.05 
•	Density curve in blue; neutron curve in red 

Track 4 
•	Archie's water saturation with max value of 1 

Track 5 
•	Bulk density curve 
•	Coal flag curve 
•	Values should be 0 or 1 (i.e., step line curve) 
•	Coal is considered anything with a bulk density less than or equal to 2.4 g/cc bulk density.



.
.
.



Plotting Well Log Using Comma-Separated Values (CSV) files in plotting well log data. 

Importing the Libraries The first step using the libraries: pandas, numpy and matplotlib. 
Will be used to load and store our data. whereas matplotlib will be used in visualizing the contents of the wells log data.

Files was gotten from:
Equinor Volve Dataset
15_9-19.csv Equinor Volve Dataset https://www.equinor.com/energy/volve-data-sharing
