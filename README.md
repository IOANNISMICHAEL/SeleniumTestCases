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
Give the name Pylot
Press Next
Select Libraries
Add External JARs
Select the Selenium IDE Jar
Press Finish
Under src folder of the Project, right-click on the created Package
Give the  name Pylot_Package
Select Class under new
Give the name SignIn 
Create a second class give the name SignUp
Right click on the src file>New
Create a Package 
Give the name utilities
Right click on utilities and create a new class
Give the name DriverFactory
Copy paste the code found under DriverFactory.txt file
Replace the directory of the WebDrivers with the ones of your local directory

 
Install TestNG
In Eclipse go to Help>Install New Software
On the UI press Add
Give Name: TestNG
Give location; http://beust.com/eclipse
Press OK
Wait to download and select TestNG
Press Next
Press Next
Accept License terms
Press OK
On Eclipse press Install anyway





******The code is ready to Run******

In order to run multiple times you need to change the email send value in SignUp class 
on Line 82 otherwise the 2nd time will fail to create a new user due to user existence 
Line 82: email.sendKeys("test6@gmail.com");

