# SeleniumTestCases
Set up Eclipse Java - Selenium Environment


Eclipse
--------------------------------------------
Download and install Eclipse from :https://www.eclipse.org/downloads/

Selenium Web Drivers
---------------------------------------------
Download Selenium Web Drivers from:
https://selenium.dev/downloads/
*Can also be found on my Github
(Download all of the them, IE, Chrome, Firefox and place them into a local file)

Selenium IDE Jar
-------------------------------------------
Download Selenium IDE from: https://selenium.dev/downloads/
*Can also be found on my Github
Save it in the same local directory as the Web Drivers

Java
-------------
Download the latest Java jdk from: https://www.java.com/en/download/





Set the Environment - Import Code
---------------------------
Open Eclipse 
Create new Java Project
Give the name Amboss
Press Next
Select Libraries
Add External JARs
Select the Selenium IDE Jar
Press Finish
Under src folder of the Project, right-click and create a Package
Give the  name TestCases
Rightclick on the package, go under New and create a class 
Give the name SignIn 
Right click on the src file>New
Create a Package 
Give the name utilities
Right click on utilities and create a new class
Give the name DriverFactory
Copy paste the code found under DriverFactory.txt file
Save the WebDrivers in a local file
Replace the directory of the WebDrivers in DriverFactory with the one of your local directory

 
Install TestNG
In Eclipse go to Help>Install New Software
On the UI press Add
Give Name: TestNG
Give location; https://dl.bintray.com/testng-team/testng-eclipse-release/
Press OK
Wait to download and select TestNG
Press Next
Press Next
Accept License terms
Press OK
On Eclipse press Install anyway





******END_OF_FILE******


