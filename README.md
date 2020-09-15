# KedarNewProject.

Project Name : SpicJet Flight Booking(Using Cucumber FrameWork)

Objective    : To book fastest and cheapest flight throug SpiceJet

Tool         : Java, Selenium, Page Object Model, Cucumber, Maven, Eclipse, Log4j.

To import the project : Open the given URL and click "Kedar-CucumberProject.zip" folder and add it to the Eclipse workspace click on import---Maven--- Existing Maven and select the project that you have downloaded from the clone URL and Update the Maven project..

Run the project : Use the  TestRunner File to run the test script.

It can be executed from "com.qa.runner" package open "TestRunner.java" Right click on the file and select "Run As" then "Junit Test".

Using pom.xml The maven surefire plugin will execute the test with the maven command as "mvn clean install".

Run through command line. Then open Run.bat file and specify the command as "mvn clean install -DbrowserValue=firefox" save and run it. The default browser is set as "chrome".

How and where to view the reports:- In console JUnit its display detailed report default cucumber reports. And removed debugging statements such as System.out.println(), but used Log4j to logging of events both in log file and console.
URL  ::  https://github.com/kedarkanchi/KedarNewProject.git
