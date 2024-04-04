# ProiectTestareManualaFinal
# Testing Project
**Date:** 20.03.2024  
**Author:** Catrinoiu Gabriela Simona  

## Table of Contents
1. [Introduction](#introduction)
   1. [Project Objective](#project-objective)
   2. [Functionalities in Scope](#functionalities-in-scope)
   3. [Functionalities and Tests Out of Scope](#functionalities-and-tests-out-of-scope)
2. [Test Process](#test-process)
   1. [Test Planning](#test-planning)
   2. [Test Analysis](#test-analysis)
   3. [Test Design](#test-design)
   4. [Test Implementation](#test-implementation)
   5. [Test Execution](#test-execution)
   6. [Test Closure](#test-closure)
   7. [Test Monitoring and Control](#test-monitoring-and-control)
3. [Test Deliverables](#test-deliverables)
   1. [Test Plan](#test-plan)
   2. [Test Conditions](#test-conditions)
   3. [Test Cases](#test-cases)
   4. [Bug Reports](#bug-reports)
   5. [Schedule](#schedule)

## Introduction
Elefant.ro is an e-commerce application which allows the users to order different types of products online.

### Project Objective
The scope of this project for ITFactory Manual and Automation Testing Course is to practice and use all the information and knowledge that I have gained through the course using a live browser application. This project consists of a test plan which describes the strategies and the process used to plan, organize and execute the test process for Elefant.ro browser application, Login module.

**Tools:** Jira, Postman, MySql  
**Functional Specifications:**
The below stories were created in Jira and describe the functional specifications of the login module, for which the final project is performed upon. Stories can be found [here]( https://itfclasses.atlassian.net/jira/software/c/projects/SCTT/boards/167/timeline).

### Functionalities in Scope
The features of Login module were written in the software requirement specification and have to be: API testing, Functional testing and GUI testing.

### Functionalities and Tests Out of Scope
- All the other features of Elefant website except Login module menu.
- Only web application will be tested.
- There is no automation testing available.
- Non-functional testing such as performance testing is beyond the scope of this project.

## Test Process

### Test Planning
The Test Plan is designed to describe all details of testing for all the modules from the Elefant application. The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found [here](link_here).

**Roles and Responsibilities:**
| Roles              | Responsibilities       |
|--------------------|-------------------------|
| Product Owner      | Andy Sinpetrean        |
| Project Manager    | Gabriela Radulescu     |
| QA Engineer        | Simona Catrinoiu       |
| Senior QA Engineer | Vlad Corcodel          |

**Entry Criteria:**
- The functional specification is defined in advance and all the roles for the project are allocated.
- The risks were detected and diminished.

**Exit Criteria:**
- All test cases have been executed.
- The QA team has closed all the resolved bugs, after re-testing them.
- The bugs which were not resolved do not present any high risk.
- No major risk remained unsolved.
- The deadline was successfully reached.

**Risks:**
*Project risks:*
- There is only one inexperienced tester in the Quality Assurance team.
- The test environment is currently unavailable.
*Product risks:*
- The release of the confidential employee information is breached by the software security.

### Test Analysis
The test conditions will be created after the business requirements will be analyzed.
**Test Conditions:** can be found [here](https://itfclasses.atlassian.net/projects/SCTT?selectedItem=com.thed.zephyr.je__cycle-summary)

### Test Design
- API test cases will be written in Postman
- Graphic User Interface test cases will be created in Zephyr Squad
- Functional test cases will be written in Zephyr Squad
- Black box testing techniques such as Boundary Value Analysis and Equivalence Partitioning will be used for creating test cases

### Test Implementation
Before the test cases are executed, I need to check that:
- The test environment is functioning (Elefant.ro Login Module)
- The access to the test environment is possible using the credentials (username: Admin, password: admin123)
- All the test cases were added to Jira in Cycle Summary

### Test Execution
- All the test cases are executed, including the API test cases.
- Bug reports are created when needed.
Test cases are executed on the created test Cycle summary TestCycle1.
Bugs have been created based on the failed tests.
The following is a summary of the bugs that have been found: [here](https://itfclasses.atlassian.net/jira/software/c/projects/SCTT/boards/167/timeline?issueType=10004)

### Test Closure
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team.
The traceability matrix was generated and can be found [here](https://itfclasses.atlassian.net/projects/SCTT?selectedItem=com.thed.zephyr.je__traceability-project-level).
Test execution chart was generated and can be found below.
The final report shows that a number of 2 tests have failed of a total of 12. A number of 2 total bugs were found, from which the priority is: 1 is high and 1 is medium.

### Test Monitoring and Control
Periodic reports are generated every two weeks in order to check the status of the project.

## Test Deliverables

### Test Plan
ITFactory Project Manager expects this test plan to be delivered until the sixth week of the Manual Testing Course.

### Test Conditions
(To be filled)

### Test Cases
(To be filled)

### Bug Report
(To be filled)

### Schedule
| Tasks                                                  | Date       | Executed by      |
|--------------------------------------------------------|------------|------------------|
| Run GUI Testing for User management module             | 05.03.2024 | Simona Catrinoiu |
| Run GUI Testing for Job module                         | 08.03.2024 | Simona Catrinoiu |
| Run Functional testing for Job Titles and Job Category submenu | 12.03.2024 | Simona Catrinoiu |
| Run Functional testing for Employment Status and Pay Grade submenu | 18.03.2024 | Simona Catrinoiu |
| Export daily report                                    | 18.03.2024 | Simona Catrinoiu |
| Run Functional testing for User Management and Work Shifts | 19.03.2024 | Simona Catrinoiu |
| Export traceability and general reports                | 19.03.2024 | Simona Catrinoiu |
| Handover the project                                   | 23.03.2024 | Simona Catrinoiu |
