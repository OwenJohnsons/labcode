Files in archive;
	
	CalibrationPoint-*.csv
		4 calibration points, one point per file. These files contain temperature and diode circuit voltage data.
		The diode was connected to the driver circuitry using long leads and placed on the table (room temp)/ in a bath of water with ice/ in a bath of boiling water/ in a bath of liquid nitrogen and the voltage was measured.
		File contains one row and four columns of data; 1: the temperature of the bath (measured using an infrared thermometer, except the liquid nitrogen as it could record that low) 2: temperature error (error of the thermometer. No liquid nitrogen temp error available so left at 0) 3: the average of 1000 voltage measurements from the diode circuit at this temperature and 4: the standard deviation of these 1000 measurements.
	
	CalibrationMassData.csv
		File contains mass and force sensor voltage data.
		Various combinations of weights were first weighed on a scale and then suspended from the force sensor. The weight of the weights was recorded along with the voltage output of the force sensor. 
		File contains four columns of data; 1: mass of the weights, 2: mass weight error (half smallest unit the scale can measure), 3: Average of 300 voltage samples from the force sensor, 4: standard deviation of the voltage samples.

	Temp+Force_**_***C.csv
		20 files, 10 for copper, 10 for aluminium, containing temperature and force data.
		The diode thermally greased into a block of the sample material (Cu/Al) was suspended at various heights over the liquid nitrogen bath until its temperature came to equilibrium at approximately the temperature given in the title of each file. The diode and sample block were then dropped into the bath. The voltage output of the diode and the force sensor were record over this entire process from about 120 seconds before the diode was dropped into the bath to about 120 secs after. 
		File contains five columns of data; 1: time since the start of recording, 2: Average of 100 force sensor voltage samples, 3: standard deviation of the force voltage samples, 4: Average of 100 diode circuit voltage samples, 5: standard deviation of the diode samples.
	
	Auxiliary Information:
		Mass of copper block: 		25.78 +- 0.005 grams
		Mass of Aluminium block:	11.22 +- 0.005 grams
