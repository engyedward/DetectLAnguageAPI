# Introduction
This is an API test automation framework, using RestAssured library, including tests for Detect Language API.
The framework also includes logging for commands done throughout the test, and issues if any, and also includes reporting for test execution using Extent library and send email with the execution report and using Send Grid.


# Pre-requisites
**First: Java Development Kit**

This solution works with Java JDK version 11, You need to check your installed version by using this cmd line : java -version
If it’s not installed, you can install it from this link https://www.oracle.com/eg/java/technologies/downloads/#java11-windows assuming you’re working on windows
Then, open environment variables and check “System Variables” to make sure that JAVA_HOME exists and its value is the local path of your installed jdk

**Second: Maven**

Download Maven from this link https://maven.apache.org/download.cgi
Then, open environment variables and check “System Variables” to make sure that MAVEN_HOME exists and its value is the local path to your Maven bin folder
Also, under “System Variables”, Edit “Path” and add “%JAVA_HOME%” and “%MAVEN_HOME%”

**Third: IDE**

Install IDE, recommended “intellij community edition” through this link https://www.jetbrains.com/idea/download/?section=windows


# Build and Test
Open intellij, Clone the project, Build the project and it’s ready to contribute. 

# Architecture Explanation
* Maven for managing project build
* RestAssured For testing Restful API
* TestNG for Testing framework and useful tests annotations
![img_3.png](img_3.png)

Other useful libraries
* Extent Report for creating test execution reports
* SendGrid to send email with the test execution reports
* Lombok to avoid boilerplate code
