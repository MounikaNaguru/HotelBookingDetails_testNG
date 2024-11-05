Find Hotel Availability
---------------------------
Case Study: Find Hotel Availability

Problem Statement:  
--------------------
Hotel Availability Automation

1) Availability of hotel rooms in next week (e.g. 27 July Check in and 28 July Check out) for a specific city. Ex: Mumbai

2) Get the Price of All the Hotels

3) Sort the hotels by rating

4) Check if the first 5 hotels belongs to the specific city searched for. Ex: Mumbai

Suggested site: https://www.trivago.in/

Detailed Description:

Open the application https://www.trivago.in/ in chrome or fire fox browser.
In search field, enter City “Mumbai” as destination.
Select Check-In Date for the next week (e.g. 27 July)
Select Check-Out Date for the next week (e.g.28 July)
Select Adults 1
Select Rooms 1
Click on Apply.
Click on Search.
Select Sort By “Rating only”
Get the list of Rent of the hotels displayed.
Check that the all the ratings of the hotels is in descending order (e.g. 10.0>9.8>9.6..)
Close the browser
Key Automation Scope:

Multiple browser handling
Assign synchronization technique
Use Calendar or Date-Picker
Navigation to Home page
Exception Handling
Locating Elements
--------------------------------------------
Implement reusable methods separately to improve more readability.
Multibrowser execution- Handle at least two browsers (Firefox and IE/Chrome). Optional - desired capabilities/driver setup
Data driven concept - Input data should be imported from an external excel sheet (Ex: using Apache PoI libraries in case of Java) or Properties file or flat file
Handle exceptions with exception handling & error messages
Use relative path
Used ID or Name locator instead of XPATH
Coding standard should be followed, which includes variable, object naming convention, script headers & comments
All scripts / business components/Test results should be available in their respective folders
Functions should have header, comments wherever applicable to improve readability and maintainability
Handle page synchronization issues using industry standard best practices. UseTimeout instead of Sleep statement wherever applicable.
Validation messages should be logged into the Test Results or Console output
