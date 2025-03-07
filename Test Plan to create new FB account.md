Test Plan to Create new account
1.	Objective
	Users can successfully create a new Facebook account by inputting required information (name, valid email, phone number, password, date of birth, gender) 

2.	Test Scope 

	2.1 In scope/ Feature to be tested
	-Validate users are able to input information required to create an account
	- Validate invalid information are rejected such as invalid email, weak password

	2.2 Out of Scope/ Feature not to be tested
	-Login in page, Profile settings, Facebook page UI

3.	Test Strategy
	
 3.1 Level of Testing
	-Unit
	- Integration
	- System
	- Acceptance
	
 3.2 Types of testing
	- Functional Testing (Smoke,  Regression, Alpha, Beta)
	- Non Functional (Performance, Security, Compatibility, Usability Test)
	
 3.3 Test Design
	- Manual Testing from HP ALM
	- Automation testing with Selenium
	
 3.4 Configuration management
	- Version management using Github
	
 3.5 Test Metrics
	- Traceability Metrics
	
 3.6 Terminology
	- Standard terminology used. Example: UI, valid information, invalid information input
	
 3.7 Automation Plan
	- Automotive repetitive test cases such as successful account creation after putting in all the required information using Selenium Web Drive
	
 3.8 Automated Tool
	- Selenium Web Drive
	-HP ALM


4.	Base Criteria 
	4.1 Entry Criteria
	- Sign Up page creation is complete
	- Functional requirement for sign up page is reviewed and approved
	- Test Script is created and approved
	- Test platform (mobile browser, web browser)  is setup and ready to use
	- Tools like Selenium and HP ALM is installed and ready to use
	- Test data (valid and invalid credential) is prepared and approved.
	4.2 Exit Criteria
	-All the test cases have been executed successfully
	-All the major bugs are fixed 
	-No new defects or bugs detected during regression and adhoc testing
	- UAT is completed and approved by client
	- Test report prepared and submitted to internal team and client
	- Approval received from QA Lead and project manager

5.	Deliverables
	- Test Case/ Test scripts
	- Traceability Metrics
	- Bug report with severity level
6.	 Test environment
   	-  OS (Windows, MAC OS, iOS, Android)
	- Browser: Chrome, Firefox, Edge, Safari)
7.	Resource Planning 
	-	QA with expertise in web automation testing
	-	Tools like Selenium, Web drive is available
	-	Different devices like Laptop and phone is available for testing the account creation page testing
8.	 Scheduling
	-	First week: Unit Testing/ Functional Testing
	-	Second week: Non functional testing 
9.	Staffing and Training
	-	One lead to over sea the testing team
	-	2 manual tester for functional validation
	-	1 QA for automation testing 
Training for Selenium, HP ALM, Web drive will be provided to the testing team prior to the project

 10.	Risk and Contingencies
	10.1 Risk 
	- Server down
	- Delay in Test script approval
	- Unavailability of resources
10.2 Contingencies
	- Progress report daily to Project Manager and PM’s intervention if delay in approval
	- Utilize DEV/ QA/ Staging  environment in case Server is down

12. Assumption
	- Account creation page  requirement is completed and approved before moving on to testing
	- Test script is ready to perform the testing 
	- Test environment is stable throughout the project

13. Approval Information
- QA Team Lead
- Project Manager
