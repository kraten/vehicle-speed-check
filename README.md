Vehicle Speed Detection

Technologies used :
	1. Python
	2. opencv
	3. dlib

Tasks breakdown:
	1. Vehicle Detection
		- We are using Haarcascade classifier to identify vehicles.

	2. Vehicle Tracking - ( assigning IDs to vehicles )
		- We have used corelation tracker from dlib library.

	3. Speed Calculation
		- We are calculating the distance moved by the tracked vehicle 
		  in a second, in terms of pixels, so we need pixel per meter
		  to calculate the distance travelled in meters.
		- With distance travelled per second in meters, we will get the 
		  speed of the vehicle.
