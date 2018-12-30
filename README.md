# Driver App


Driver Time Tracking Application for Root Internship by  Taylor Kilgore
=======================================================================

Introduction
-------------

This application for the Root Insurance internship is coded in JavaScript with Jquery and a Bootstrap UI.
Bootstrap was used to create a more user-friendly interface. For this project, I took a bottom-to-top approach by starting with
the simplest element, time, and then working up to the submit button were the driver is added, compared, and displayed.

Time
----- 

The approach taken to this problem was to outline all the functions for the drive by first getting the time which would frame the reference point to get the information for the driver. 'var parts= time.split(":");' finds the time from the start and end time by splitting parts into an array and multiplying the first part into an array.

Driver
------

The drivers are parsed into an array for the drivers to be added. The add() function gets the time from the getDriveTime and mph from getMPH(distance, time); . The statement, 'if (time<0 ) return;' (line 69), doesn't process the driver if the time is negative. the driver The driver is then  constructor is created adding a new driver . the new driver is then compared to previous to drivers  and adds the distance and the time which in turn helps calculate the mph. 



Submit  Button 
---------------

The values from the UI are passed into the submit button upon click of the button on the UI. The Data is gathered
and then passed into the add function.if (!Driver) checks for invalid input and clears for any correct input

the check for the mph to be greater then 5mph or less then 100 mph. If false, it returns the text declaring the MPH and distance. 
