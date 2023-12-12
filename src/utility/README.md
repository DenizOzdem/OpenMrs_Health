# TechnoStudyTr Project
# Project :
Performing tests at https://openmrs.org/tr/.

 ## Definition :
OpenMRS is an open-source electronic health record system designed to manage, store
and share patient data for healthcare organizations. It is particularly tailored to
improve healthcare services in low-income countries. This platform supports essential
functions such as digitizing medical records, patient tracking, treatment planning and
the analysis of health data. The OpenMRS Project is open source and developed by a
community where software developers, healthcare professionals, and volunteers collaborate
to enhance data management in healthcare services. OpenMRS provides a user-friendly
interface and is adaptable for different healthcare organizations.

Project Details:

* OpenMrs Demo Environment Test
* 10 user stories are at project backlog in Jira
* Aimed to finish following user stories in the spring

1. Checking login errors
2. Login to the system
3. Logout from the system
4. Patient Registration 
5. My Account 
6. Search on the patient list 
7. Delete patient 
8. Patient listing
9. Combining patient records (MERGE) 
10. Wrong time zone when you make a patient appointment

### Requirements : 
* JDK1.8se
* org.seleniumhq.selenium:selenium-java:4.11.0
* org.slf4j:slf4j-nop:1.7.30
* commons-io:commons-io:2.11.0
* org.testng:testng:6.14.3

### Set up  : 
* Follow the steps :
* Install IntelliJ IDEA Community Edition
* Install Java 8SE (JDK 1.8)'i (JDK 20)
* Create Maven project at IntelliJ
* Use TestNG

If you use Maven for project dependencies, update pom.xml folder, add these dependencies

<dependencies>
    <!-- Selenium WebDriver -->
    <dependency>
        <groupId>org.seleniumhq.selenium</groupId>
        <artifactId>selenium-java</artifactId>
        <version>4.11.0</version>
    </dependency>

    <!-- TestNG -->
    <dependency>
        <groupId>org.testng</groupId>
        <artifactId>testng</artifactId>
        <version>7.4.0</version>
    </dependency>

 <!-- SLF4J (Simple Logging Facade for Java) -->
 <dependency>
     <groupId>org.slf4j</groupId>
     <artifactId>slf4j-nop</artifactId>
     <version>1.7.36</version>
 </dependency>

 <!-- Commons IO -->
 <dependency>
     <groupId>commons-io</groupId>
     <artifactId>commons-io</artifactId>
     <version>2.11.0</version>
 </dependency>

 <!-- Diğer bağımlılıklarınız -->

</dependencies>


### Running the Program : 
* All test cases are running via intellij
* Test are developed with Xml, dataProvider and priority order
* All user stories and test cases planned and assigned via Jira
* Reports created with excel

## Author :
* QA Deniz Özdem      denizozdem@gmail.com

## Version History : 
v.01= First edition
v.02= Updates and fixes
v.03= Last version



