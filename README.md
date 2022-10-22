# Rest-Assured-Junit
One of the most popular REST API Automation Testing libraries is Rest Assured Tutorial. RESTful Web Services are tested using the Java-based package Rest-Assured. In order to access REST web services, this library acts like a headless client. To transmit to the Restful server, we may generate HTTP Requests with a great deal of customization.

Technology:

Tool: REST Assured

IDE: Intellij

Build tool: Gradle

Language: Java

Test_Runner: TestNG

Prerequisites

Install jdk 8 or any LTS versio

Configure JAVA_HOME and GRADLE_HOME

Download Allure 2.18.1 and configure environment path

Stable internet connection

Install Rest Assured Framework

Open Intellij

Go to File > New > Project

Select Gradle and click next

Give project name as Rest-Assured-API-Automation-Demo

Click on the Finish button

Now go to build.gradle file and add following lines:

// https://mvnrepository.com/artifact/io.rest-assured/rest-assured
    testImplementation group: 'io.rest-assured', name: 'rest-assured', version: '4.3.3'
    // https://mvnrepository.com/artifact/commons-configuration/commons-configuration
    implementation group: 'commons-configuration', name: 'commons-configuration', version: '1.10'
    
    Config environment variable:
    
     Now create a file named config.properties under
     
src > test > resources folder

 Add this line:
 
baseUrl=https://customer-test-api.herokuapp.com

 Then create a java class named Customer under test > java folder
 
 Run the Automation  following command
 
 gradle clean test 
 
 Report
 
 ![testrunner](https://user-images.githubusercontent.com/61340440/197320236-596d2c96-b2e4-4c37-b709-5894befe3149.JPG)
