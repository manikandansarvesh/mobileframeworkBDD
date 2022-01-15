mobileframeworkBdd

	•	Appium mobile test automation framework with Page Object Model design using
	•	Java + Cucumber + Maven + JUnit.
	•	Framework follows many of the industry best practices and supports Android and iOS in a single code base.


Technologies/Tools used in building the framework

	▪	Appium - Mobile Automation 
	▪	Maven - Build automation tool
	▪	Java - Programming language
	▪	Cucumber - BDD
	▪	JUnit - Unit testing framework
	▪	Log4J - Logging framework
	▪	Cucumber Reports - Reporting framework
	▪	GitHub - Version control
	▪	Framework implements below best practices
	⁃	Code reusability
	⁃	Code readability

	▪	Parameterization using TestNG XML and deviceconfig.properties
	▪	Abstraction layer for static text
	▪	Supports iOS and Android
	▪	Scrolling for both Android and iOS (using touchaction, uiScrollable, mobile:scroll)
	▪	Start Appium server programmatically
	▪	Supports Cucumber-HTML-Reporter plugin
	▪	Integrated with Log4J2 Logging framework
	▪	Implemented PMD Plugin for Code Analysis

Steps to execute

	Clone this code and navigate to project Folder

Pre-Requisties

 	 1.Change the platformName, udid, deviceName in 	initializeGlobalParams(),GlobalParams in com.qa.utils;
 	 2.Based on the operating system change the behaviour in start 	server(),ServerManger class
    Ex: For Windows —>WindowsGetAppiumService() and 
			 Mac —>MacGetAppiumService()
    For Mac users configure your java,Android and Appium path to ignore
    Error : neither android_home nor android_sdk_root environment 	variable was exported

Command to execute this project
⁃	  mvn test

To obtain PMD Results
⁃	 mvn compile site
⁃	 mvn pmd:pmd pmd:cpd











