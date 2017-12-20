# NYC_Subway_Notification_System

This repository contains the code I worked on along with two other students at NYU to make a Notification System for the NYC Subway.

Inside this folder you will find two ipython notebooks and a folder containing test user data. Please review the following instructions on how to run the code, and test it for yourself. 



## Running the code:

### Core_Code_Final.ipynb
This code handles all of the processes related to checking the MTA website for train service status, processing user data, and sending alert emails. To start the program simply run all cells. Note that this program works by running in an indefinitely loop, running once a minute (the frequency that the MTA service status page is updated), so to stop it you will have to interrupt the kernel in the Jupyter Notebook. 

### Web_interface.ipynb
This code generates the web interface by which you can enter user data to receive alerts. To run simply run the cell and follow the link generated to local host 8080 in your web browser. From there you can enter user data to receive alerts. After you enter user data you can choose to enter more or shutdown the server, you do not need to do either for the program to work. 



## Generating Alerts:

To receive alerts enter user information that meets the following conditions:
●	Use your email address 
●	Choose subway lines where the current status is not “Good Service” 
●	Set a commute time that is equal to the current time (time when “Core_Code_Final” is running) plus the “time window” variable (in Core_Code), which defines how far in advance to alert users of service disruptions on their subway lines. E.g. if the code is about to run at 12PM and time window is set to 10 minutes, users with a commute time of 12:10 will be alerted. 


If you have any questions about how to run the code contact us! 
srf366@stern.nyu.edu; yk1859@nyu.edu; fh643@nyu.edu 

