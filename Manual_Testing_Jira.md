# Testing Project for Tricentis
The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: Tricentis

Tools used: Jira, Zephyr Squad.

## Functional specifications:
The below stories were created in Jira and describes the functional specifications of the 'Automobile' module, for which the final project is performed upon.

![storiuri](https://github.com/emiliancristea11/Manual_Testing_Jira/assets/148649851/dba316de-80d2-4978-806f-ff53c90d1c01)

Here you can find the release that was created for this project:

![release](https://github.com/emiliancristea11/Manual_Testing_Jira/assets/148649851/71d6ceee-a16b-4fad-b613-a099fc05454e)

## Testing Process
The test process was performed based on the standard test process as described below.

### 1.1 Test planning <br>
The Test Plan is designed to describe all details of testing for the 'Automobile' module from the Tricentis application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here: [Test plan Tricentis Cristea Emilian.docx](https://github.com/user-attachments/files/16149954/Test.plan.Tricentis.Cristea.Emilian.docx)


1.1.1. Roles asigned to the project and persons allocated <br>

* Project manager - Vasile Poenaru <br>
* Product owner - Andreea Melchisedec <br>
* Software developer - Olaru Bogdan <br>
* QA Engineer - Cristea Emilian <br>

1.1.2 Entry criteria defined <br>
* assigning roles
* business requirements
* idetified and mitigated project risks
* test plan created
* entry requirements met
  
1.1.3 Exit criteria defined <br>
* all tests are run
* regression testing is finished
* identified and mitigated product risks
* closing report generated and sent

1.1.4 Test scope <br>
Tests in scope: <br>
* Positive/Negative testing
* Functional testing
* Usability testing
* Equivalence partitioning
* Boundary value analysis

Tests not in scope: <br>
* Compatibility(with different devices or browsers)
* Security testing
  
1.1.5 Risks detected <br>
Project risks: <br>
* Supplier issues
* Technical issues
  
Product risks: <br>
* Low usability
* Low performance
  
1.1.6 Evaluating entry criteria <br>
The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

### 1.2 Test Monitoring and Control
I performed the Test Monitoring and Control stage because it is a phase that takes place during the whole testing process with the aim of comparing actual progress and test plan.

![test metrics](https://github.com/emiliancristea11/Manual_Testing_Jira/assets/148649851/4fb0a15f-4be1-4da6-b367-b967bf54d583)

### 1.3 Test Analysis
The testing process will be executed based on the application requirements. (The requirements analysis has been done in order to implement the early testing test principle and the results can be found here - inserati linkul catre documentul de review. Parte asta specificata intre paranteze o puneti doar daca aveti cerinte si daca ati facut review).

The following test conditions were found: <br>
* Verify that an user can add new vehicle details using valid data
* Verify that an user can add new insurant details using valid data
* Verify that an user can add new product details using valid data
* Verify that an user is successfully able to select a price option
* Verify that an user is successfully able to send a quote
* Verify that an user cannot proceed to the next submenu without completing the mandatory fields in 'Enter Vehicle Data'
* Verify that an user cannot proceed to the next submenu without completing the mandatory fields in 'Enter Insurant Data'
* Verify that an user is able to select an insurance start date with any date he wishes to
* Verify that an user actually receives the e-mail he has sent
* Verify that an user is able to preview a quote before proceeding to the next submenu


### 1.4 Test Design
Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here ![image](https://github.com/emiliancristea11/Manual_Testing_Jira/assets/148649851/1e1e0410-d2b6-4866-825d-c2230e5050a0)

### 1.5 Test Implementation
The following elements are needed to be ready before the test execution phase begins:
* Execution of test scripts
* Test data preparation
* Tool configuration
* Enviroment setup
* Defect reporting
* Adherence to test procedures
* Test case execution
* Verification and validation
* Documenting and reporting

### 1.6. Test Execution
Test cases are executed on the created test Cycle summary: Automobile - Function Testing

Bugs have been created based on the failed tests. The complete bug reports can be found here: 
![image](https://github.com/emiliancristea11/Manual_Testing_Jira/assets/148649851/371d50ff-c480-4416-89e4-232a100e2344)


Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

### 1.7 Test Completion As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: 

![matrix1](https://github.com/emiliancristea11/Manual_Testing_Jira/assets/148649851/3e599ff0-8de3-4657-95ec-c9760e413b74)

Test execution chart was generated and can be found below.

![dashboard](https://github.com/emiliancristea11/Manual_Testing_Jira/assets/148649851/40a1e6d2-4377-414a-b797-eb8e94b77139)

The final report shows that a number 5 tests have failed of a total of 10.

A number of 5 total bugs were found, from which the priority is: 3 are high and 2 are medium.
