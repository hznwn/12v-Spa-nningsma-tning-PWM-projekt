The files contained within this project were created for an electric car conversion project formed within the "Project Work in Electrical Engineering" course at Uppsala University. The course is a part of the "Master's Programme in Electrical Engineering" and took place between the fall of 2022 and spring 2023.

Volvo group donated 3 cars to Uppsala University in order to remove the combustion engines and instead replace them with electric motors. 
More details about the course and program can be found below. 

In order to complete the goals of the car conversion project, a total of twelve 12-volt batteries were placed in the trunk in order to power the electric motors. The batteries were then connected in series to achieve a total of 144-volts. 

The files found within this github project pertain to the measurement of voltage across each of the 12-volt batteries.
Measuring the voltage of 12 individual batteries, at 12 V with different relative potential levels, can provide critical information when it comes to troubleshooting and solving potential problems. Voltage level can indicate whether a circuit is supplied with too much or too little voltage. In addition, it is also possible to identify which individual component may be the cause of the problem based on the voltage drop (if it has a larger or smaller voltage drop than expected.

The solution presented within the LTSpice and KiKad files was required as the voltage of all the batteries must be measured simultaneously, even when they have different "grounds" (common). Additionally, in order to gather the signals and data log and store the values, a National Instruments MyRIO was used. MyRIO is a real-time embedded evaluation board, and only supports measurements between 0-5V, so many adjustments were needed to safely ensure it could read and accept the signals from the batteries. 

All files, with exception to the group report, was created by hznwn. 

Kursplan för Projektarbete i elektroteknik:
https://www.uu.se/utbildning/utbildningar/selma/kursplan?kpid=39132&type=1

Civilingenjörsprogrammet i elektroteknik:
https://www.uu.se/utbildning/utbildningar/selma/program/?pKod=TEL2Y
