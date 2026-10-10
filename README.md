# Food_Truck_Tracker - GitHub Collaboration Demonstration
Spencer - SpencerJGreen
Liam - WickedNoPoint

## Introduction
We are building a Campus Food Truck Tracker app for the college. The App will provide real-time tracking of food trucks and their hours of availability.

## Requirements

### FR 01 - Display Location on Map - Must Have
The application shall display food truck locations on a map of the campus. 

### FR 02 - Truck Details - Should Have
When user click on a trucks location it will display the menu, hour, and location details about that truck.

### FR 03 - Vendor Accounts - Must Have
Vendors (users who manage food trucks.) will create accounts to add and remove their location from the map and upload the required truck details. There must be a login system to support this.

### FR 04 - Filters for Vendor type - Should Have
Users should be able to filter results to display vendors by types of cuisines i.e. Mexican, Japanese, or sandwiches.

Liam and I made separate branches for map services and database/authentication services.

We had a conflict due to the two of us using the same testing.txt to perform our validation testing. It was merged by accepting both changes and putting one below the other in the same file.

We will swap between blue and green by setting our config.txt file to use either deployment or production.env variables. This allows for easy changeover.