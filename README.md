# Computer-DB-CRUD-AutomationTest
CRUD Test Automation of Computer Database 


BackBase Test Automation instruction for Computer Database


Test Automation tool:Selenium Webdriver
Automation framework: Data Driven
Test Architecture:  Page Object Model(POM)
OOP: Java Programming Language
Annotation: TestNG
IDE: Eclispe
 

To run the automation test scripts you would need to download:
the latest Java libraries: https://www.oracle.com/technetwork/java/javase/downloads/jdk11-downloads-5066655.html
Eclipse IDE: https://www.eclipse.org/downloads/ (or your preferred IDE)
Selenium Webdriver jar files: https://www.seleniumhq.org/download/ 
Chrome Webdriver executable 


On successfully downloading the above;
Run the Eclipse executable to open Eclipse.
Create an Eclispse workspace
Install and configure a Maven Project within Eclipse IDE Workspace.
Import your Selenium Webdriver and Java jars into your Java project within Eclipse( in this case simple import the project provided for the CRUD test automation built to test http://computer-database.herokuapp.com/computers web app).

There two ways to execute the test scripts:
(I)Navigate to the package “com.bb.crud.qa.testcase” under src\test\java folder, right click on the package -->Select “Run AS”, then click on “TestNG. See image below.





The automated process of running the entire test suite will kick off, on completion.
You can view the test result and error(s)/failure(s),as applicable. Thus you can evaluate and trace the errors. See image below:




Please, do note that you can run an individual test case independent of the whole test suite, should you have the need to. This can be done by highlighting the method of target test case, right-click, select “Run As”menu ---> TestNG Test, which would kick off the automation of the selected test case.

Mind you, you can also view a comprehensive evaluation of test result as seen below by navigation to “test-output” folder ---> emaiable-report.html and coping the link onto a browser.





Also, be informed that this is data driven frame work, with a data file “config.properties” where you can enter/update your data input. See image below:


Happy test automation running!

You may reach me at azbaba@hotmail.co.uk, if clarification is required.










