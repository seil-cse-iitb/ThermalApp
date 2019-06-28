Project 1: Achieving Thermal Comfort:  A Systematic Approach



PATH OF THE PROJECT
Code Location-
home/stark/labThermalApp/dataExtract.py(For seil )\\
home/stark/fckServerApp/dataExtract.py(For LH)\\
home/stark/labThermalApp/Optimization.py\\
var/www/html/lab_tc_app/seating.html(seil)\\
var/www/html/tc/seating.html(LH)\\
QR code Link added in thee seil doc folder\\
Attaching paper: Achieving_Thermal_Comfort__A_Systematic_Approach.pdf \\
Presentation links: \\
https://docs.google.com/presentation/d/1bjQYQlcC7DPtzmrOQROtXntxGzQFTg9zS_vq8PHfqBo/edit?usp=sharing\\
https://docs.google.com/presentation/d/18fUhg-Dn_CCURR9FWPGre1pPb7EhzVPWw2zoic8bvyE/edit?usp=sharing\\
https://docs.google.com/presentation/d/1PrAlXBXssrG0zb6kXZIgGu4Sj9xQEiPGYpqsMK3Nxbw/edit?usp=sharing\\
Description of the codes\\

dataExtract.py - (Can be modified for any space)\\
To fetch the data from the database.
Connection with the database.
get the sensor data from db( accordingly to room configuration (row, column)).
Do interpolation from the sensor data collected
Show the data on HTML page (http://10.129.149.7/lab_tc_app/seating.html)

Optimization.py - \\
Code works for each zone (every 5 mins)
For each zone we collect number of people feeling uncomfortable and rating given by them
If number of people feeling uncomfortable is above some threshold algorithm makes smart decision to increase or decrease the temperature
Seating.html\\
To show the heat map

