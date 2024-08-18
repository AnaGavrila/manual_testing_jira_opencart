# Testing Project for Opencart
The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

**Application under test:** Opencart

**Tools used:** Jira, Zephyr Squad.

**Functional specifications:**
The stories [here](https://github.com/AnaGavrila/manual_testing_jira_opencart/blob/main/Jira.pdf) were created in Jira and describe the functional specifications of the "Orders" module, for which the final project is performed upon.
Below you can find a picture with one of the stories:
![image](https://github.com/user-attachments/assets/cf4de33e-4c5b-4c89-86e3-e05938ae6996)


Here you can find the release that was created for this project:

![image](https://github.com/user-attachments/assets/cb64d79f-3645-4a8e-a357-6ce3892ff607)


## Testing process
The test process was performed based on the standard test process as described below.

### 1.1 Test planning
The Test Plan is designed to describe all details of testing for all the modules from the JPetStore Demo application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here (inserati link catre documentul cu planul de testare)

#### 1.1.1. Roles asigned to the project and persons allocated
<table>
<tr><td>Project manager</td> <td>Barbu Alexandru</td></tr>
<tr><td>Product owner</td> <td>Popescu Marius</td></tr>
<tr><td>Software developer</td> <td>Ionescu Mihaela</td></tr>
<tr><td>QA Engineer</td> <td>Gavrila Ana</td></tr>
</table>

#### 1.1.2 Entry criteria defined
<table>
<tr><td>Requirements Documented: All functional and non-functional requirements are fully documented, reviewed, and approved by stakeholders.</td></tr>
<tr><td>Environment Ready: Development environment is set up with the necessary software, tools, and access rights.</td></tr>
<tr><td>Technical Specifications Available: Detailed technical specifications, including architecture diagrams, data models, and API contracts, are completed.</td></tr>
<tr><td>Team Trained: The development team has been briefed and trained on the project scope, technology stack, and tools.</td></tr>
</table>

#### 1.1.3 Exit criteria defined
<table>
<tr><td>Code Complete: All features planned for the release are developed, and the code is frozen. </td></tr>
<tr><td>Unit Testing Done: Developers have completed unit testing, and all tests have passed with an acceptable threshold. </td></tr>
<tr><td>Environment Stable: Test environment is set up, and all components are functioning as expected.</td></tr>
<tr><td>Test Cases Written: All test cases for the features being tested are written, reviewed, and approved.</td></tr>
<tr><td>Test Data Prepared: All necessary test data is prepared and validated for use in the testing phase.</td></tr>
</table>

#### 1.1.4 Test scope
**Tests in scope:**
(descrieti aici toate testele pe care intentionati sa le faceti. Puteti include functionalitati din aplicatie, tipuri sau tehnici de testare, dispozitive pe care veti testa etc)

**Tests not in scope:**
(descrieti aici toate testele pe care NU intentionati sau nu puteti sa le faceti. Puteti include functionalitati din aplicatie, tipuri sau tehnici de testare, dispozitive pe care veti testa etc)

#### 1.1.5 Risks detected
**Project risks:**
<table>
<tr><td>Lack of personnel – delays in product delivery. </td></tr>
<tr><td>Team conflicts – decrease in the quality of work and collaboration. </td></tr>
<tr><td>Incorrect attitude towards the testing process – insufficient identification of defects. </td></tr>
<tr><td>Product launch delays – loss of market opportunities.</td></tr>
<tr><td>Unclear business requirements – development of a product that does not meet user needs.</td></tr>
</table>

**Product risks:**
<table>
<tr><td>Low code quality – increase in the number of defects and performance issues. </td></tr>
<tr><td>Encountering more defects – extending the time required for testing and fixes. </td></tr>
<tr><td>The application does not function according to business requirements – dissatisfaction among clients and end users.</td></tr>
<tr><td>Low usability – difficulties in using the application and loss of users. </td></tr>
</table>

#### 1.1.6 Evaluating entry criteria
The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

### 1.2 Test Monitoring and Control
![image](https://github.com/user-attachments/assets/5bca4b6f-94cc-4993-bec8-7afab6ce3b0d)

### 1.3 Test Analysis
The following test conditions were found:

![image](https://github.com/user-attachments/assets/0e24a9f6-812d-4f23-8556-f7230c3ec9e6)


### 1.4 Test Design
Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed [here](https://itfclasses.atlassian.net/projects/SAG?selectedItem=com.thed.zephyr.je__test-cases)

### 1.5 Test Implementation
The following elements are needed to be ready before the test execution phase begins:

User Registration

Product Search

Checkout Process

Login with Invalid Credentials

Cart Management


### 1.6. Test Execution
Test cases are executed on the created test Cycle summary: V1

Bugs have been created based on the failed tests. The complete bug reports can be found here:
  [orders](https://github.com/AnaGavrila/manual_testing_jira_opencart/blob/main/ZFJ-Cycles-08-18-2024%20%202.pdf), 
  [returns](https://github.com/AnaGavrila/manual_testing_jira_opencart/blob/main/ZFJ-Cycles-08-18-2024%203.pdf), 
  [gift vouchers](https://github.com/AnaGavrila/manual_testing_jira_opencart/blob/main/ZFJ-Cycles-08-18-2024.pdf), 
  [voucher themes](https://github.com/AnaGavrila/manual_testing_jira_opencart/blob/main/ZFJ-Cycles-08-18-2024%204.pdf).

The following is a summary of the bugs that have been found

![image](https://github.com/user-attachments/assets/143bc9f8-adbd-4739-a8e6-4be1ae67aea0)

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

### 1.7 Test Completion
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team
The traceability matrix was generated and can be found here:

![image](https://github.com/user-attachments/assets/e83090d2-71c8-4c49-9653-a16b62753884)


Test execution chart was generated and can be found below.

![image](https://github.com/user-attachments/assets/125564c4-c0fd-4272-a33e-ffe7ed25bc07)


The final report shows that a number 6 tests have failed of a total of 10

A number of 6 total bugs were found, from which the priority is: 5 are high and 1 is low.

In the presented project, we have 3 stories, of which 2 are covered by tests.
Total number of tests: 10
Total number of tests executed: 10
We have identified 6 bugs that could severely affect the user, as they will not allow them to perform certain actions on the platform—actions that depend on the proper functioning of the application for both the client and the user.
