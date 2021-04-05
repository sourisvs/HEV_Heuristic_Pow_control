# HEV_Heuristic_Pow_control
Basic rules-based power control strategy for a particular HEV Model, based on look-up tables of engine and battery-motor parameters
<br />**for obtaining vehicle data**<br />
(All look up tables and vehicle data including the model configuration and other parameters are taken from the ADVISOR 2.0 Simulink programme, kindly download it if you want to get relevant data.)
<br />**for the drive cycle**<br />
Ensure the drive cycle is saved as csv format with just 2 columns, time and speed, name the speed column as "Speed", so that it can be easily read by the code without any hassle
<br /> The other files uploaded are vehicle parameters extracted from ADVISOR ready to use into the code. The characteristics excel file contains all the data that has directly been mentioned in the code itself The nomenclature is as follows: <br /> fc: Fuel converter or engine <br /> mc: Motor controller <br />ess : energy storage system or battery <br /> fc_gs: Fuel consumption in gram per second<br />nox : NOx emissions in g/s <br /> hc: Hydrocarbon emissions in g/s
