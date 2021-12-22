# Covid_Vaccination_tracker
The entire world is struggling to get immune against coronavirus by opting for the available covid-19 vaccine as soon as possible. Many countries have started the vaccination program during late 2020 and some of them have successfully vaccinated their entire population by May 2021. India has also started the vaccination drive and with each passing days, more citizens are being vaccinated. Due to the huge population, it is getting difficult to find a slot for the vaccination. The government had made it clear that citizen would be able to take vaccine only by booking online appointments on COWIN portal.

This program is to make us aware of API, released by the government of India, in the Public domain. We will learn to use Python to create a script which will send API GET request (using Python’s requests module) and fetch the JSON data as a response. This code requires the area Pincode and the date for which you want the availability of the vaccine.


Input Required: Area Pincode, Date

Output: List of all the Vaccination center(s) name along-with date-wise data like type of vaccine, minimum age, available slot.


Enter the pincode for which you want the status => 248005

Enter the Date to get status (Date format: DD-MM-YYYY) => 23-12-2021


                                       *>>>>>>    RESULTS   <<<<<<<*
-------------------------------------------------------------------------------------           
Date: 23-12-2021 | Pincode: 248005 
Total centers in your area is: 4
------------------------------------------------------------------------------------
   

[1] Center Name: SC Majri Mafi
------------------------------------------------------------
   Date      Vaccine Type    Minimum Age    Available
  ------     -------------   ------------   ----------
 23-12-2021    COVAXIN          18              0
 23-12-2021   COVISHIELD        18              0

[2] Center Name: UPHC KARGI
------------------------------------------------------------
   Date      Vaccine Type    Minimum Age    Available
  ------     -------------   ------------   ----------
 23-12-2021    COVAXIN          18             249
 23-12-2021   COVISHIELD        18             200

[3] Center Name: Nehrugram PHC
------------------------------------------------------------
   Date      Vaccine Type    Minimum Age    Available
  ------     -------------   ------------   ----------
 23-12-2021   COVISHIELD        18             398
 23-12-2021    COVAXIN          18             398

[4] Center Name: UPHC Deepnagar
------------------------------------------------------------
   Date      Vaccine Type    Minimum Age    Available
  ------     -------------   ------------   ----------
 23-12-2021    COVAXIN          18             250
 23-12-2021   COVISHIELD        18             200


                                                      Thanks
