# __Test Plan__
### Project name: campusmarconiverona.moodlecloud.com
### Group: Gruppo4
### Focus: Test Plan

|Version|Date|Author|Change Description|
|:-:|:-:|:-:|:-:|
|1|Insert date|Pietro Zecchin|First testing|
|2|Insert date|Pietro Zecchin|Test of the rng of the quiz|
|3|Insert date|Pietro Zecchin|Corrections of errors in lessons|


# __TABLE OF CONTENTS__

#### [Identifier](#Identifier)<br>
#### [Introduction](#Introduction)
- [Items and Features tested](#Items-and-Features-tested)
- [Test Specifications](#Test-Specifications)
- [Test Reports](#Test-Reports)
- [Project Plan](#Project-Plan)
- [Quality Assurance Plan](#Quality-Assurance-Plan)
#### [Items and features tested](#items-and-features-tested)
- [User Website](#User-Website)
- [Bulletin Board](#Bulletin-Board)
#### [Approach](#Approach)
- [Strategy](#Strategy)
- [Techniques/tools](#Techniques/tools)
- [Test Goals](#Test-Goals)
#### [Required Resources](#Required-Resources)
- [Human Resources](Human-Resources)
- [Material](Material)

# __Identifier__
### Gruppo4
## __Introduction__
This exercise essentially discovers faults and failures in the software. Faults lead to failures and testing is necessary to eliminate these errors in the software development process. The following document outlines the testing procedures for the Gruppo4 software project. 
## Items and features tested
During the test plan we tested different parts of the service including:
- Course making
- Questions pools
- RNG of questions pools
- Lesson making
- Badge making
- Certifications making
## Test Specifications
We included in our testing different parts provided by the hosting service made by moodlecloud.com including:
- xml tables downloading
- system administration 
- Signing in students, teachers, administrators
- File uploading services
- Awards
## Test Reports
The only problem encountered was the compatibility of the service with our system solved throught defining a python script for the channeling a xml downloaded file into a html page.
This particular service was not obligatoru however we chose to do it for the fluidity of the service. 
## Project Plan
The testing was up untile the end of the project even during developing we had tester testing it.
## Quality Assurance Plan
The service is online and ready to be used, we are committed to ensuring that the result is close to perfection and we expect the quality to be very high.
## __Items and features tested__
## User Website

User website testing takes place in the integration and system testing phases. During integration, the tester will test functions of the system and how the system behaves with additional features. During system testing, the team will test the system as a whole and cross-check the results with the requirements.<br>
Test items:
- Verify user as UMKC student
- User asks a question
- User reads answers to previous questions
## Bulletin board
Testing takes place in the integration and system testing. The tester will test functions of the project during integration,  will retest them after features are added to make sure they still function correctly.  
System testing will test all aspects of the system and cross-check them with the requirements document to ensure that the client’s requirements have been fulfilled. 

Test items:

- Provider create a new course
- Providers and students ask questions about the lessons
- Provider delete attemps in a test
- Provider add new questions to the pools
- Provider posts comment
- Provider adds a teacher user

## __Approach__

## Strategy
The testing approach includes team members role-playing by acting as users of the website and bulletin board participants. The activities they carry out will be similar to activities carried out by website users and bulletin board members. These include creating new courses, asking questions on the bulletin board, delete tests, performing administrative functions and other user activities. Team members will also create unexpected scenarios such as invalid input, to test how the system will respond to such scenarios.System testing will be performed by the group to measure how the system fulfills the requirements. Team members will be required to provide input on the systems functionality to determine if it measures up to the client’s expectations.  

## Techniques/Tools
Developers will perform unit tests to check code functionality and execution of the software, and perform white-box testing. They will also perform necessary NUnit and regression tests as they develop the code.
Testers will develop test cases and perform black-box testing. Testers and team members will also go through the code to find bugs and errors that the developers might not detect.
## Test Goals
The goals of this testing exercise include finding various user situations and testing against these situations in order to discover any errors that may cause failures. The ultimate goal is to ensure that the team delivers an error-free functioning system. 
## Human Resources
- Pietro Bonetti
- Pietro Zecchin
- Giovanni Rizzotti
- Cristiano Picilli
- Diego Donatelli
## Material
- Access to the admin system of campusmarconiverona.moodlecloud.com
- Access to html, xml, excel test programs
- Access to student and teachers emails to try enroll them