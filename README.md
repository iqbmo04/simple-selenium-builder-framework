simple-selenium-builder-framework
======================
Selenium test framework designed to run recorded tests on SauceLabs.

## Use cases

1.  If you need to monitor 100 different websites and just check for one simple thing on each one, then just record 100 Selenium builder recordings, export them to Java/TestNG format, and then drop them into this framework.
2.  If you have a website with 3 text fields on it and you want to test all combinations of entering data into those fields without using unit test parameterization, then just create 6 Selenium Builder recordings that represent those combinations and dropt them into this framework.


## Instructions

This project will run within Eclipse, IntelliJ IDEA, or from the command line using Maven.

1.  Import this GitHub archive into Eclipse as a "Maven project".
2.  Create as many 'Selenium Builder' scripts as you want and place them in the "src/test/java/qa/se/builder" folder,
      just like what is provided in the example.
3.  Run-As "mvn.bat test", otherwise known as the goal "test" executed by Maven.
4.  View the HTML test result report in the target folder that is generated at runtime.

## using jenkins

This framework is designed to run multi-threaded tests against SauceLabs.
