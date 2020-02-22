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
1.Open Eclipse 
2.Create new Java Project
3.Give the name Amboss
4.Press Next
5.Select Libraries
6.Add External JARs
7.Select the Selenium IDE Jar
8.Press Finish
9.Under src folder of the Project, right-click and create a Package
10.Give the  name TestCases
11.Rightclick on the package, go under New and create a class 
12.Give the name SignIn 
13.Right click on the src file>New
14.Create a Package 
15.Give the name utilities
16.Right click on utilities and create a new class
17.Give the name DriverFactory
18.Copy paste the code found under DriverFactory.txt file
19.Save the WebDrivers in a local file
20.Replace the directory of the WebDrivers in DriverFactory with the one of your local directory

 
Install TestNG
--------------------
1.In Eclipse go to Help>Install New Software
2.On the UI press Add
3.Give Name: TestNG
4.Give location; https://dl.bintray.com/testng-team/testng-eclipse-release/
5.Press OK
6.Wait to download and select TestNG
7.Press Next
8.Press Next
9.Accept License terms
10.Press OK
11.On Eclipse press Install anyway





******END_OF_FILE******


