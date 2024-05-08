# CAS_Project
PROJECT : Tru Time Case Study

OVERVIEW
     This project aims to automate the TruTime application of Cognizant using Selenium WebDriver. The automation process involves navigating through the Be.Cognizant portal, extracting user information, verifying OneCognizant display, searching for TruTime application and validating the details.

LIBRARIES AND DEPENDENCIES
* Maven Repository: Maven 3.12.1
* Apache POI: 5.2.5
* TestNG: 7.10.0
* Selenium WebDriver: 4.18.0
* Loggers: 2.23.0

AUTOMATION FLOW
1. Navigate to Be.Cognizant portal.
2. Extract user information from the profile.
3. Verify the presence of OneCognizant link.
4. Click on OneCognizant link.
5. Search for TruTime in the search bar.
6. Click on TruTime and navigate to the application.
7. Get the current week and validate it with the System date.
8. Get the current date and month. Validate it with the System date.
9. Get the backDated Topup date and validate it.
10.  Get all the legends and print it.

LIBRARIES EXPLANATION
* Maven Repository: Used for project management and dependency resolution.
* Apache POI: Handles Excel operations for data-driven testing.
* TestNG: Facilitates test case organization and execution.
* Selenium WebDriver: Automates browser interactions.
* Loggers: Facilitates logging for better debugging.

PROJECT EXECUTION
Step 1: Launch the Eclipse IDE
Step 2: Right-click on the project in the Project Explorer. 
Choose Maven -->Update Project. Click OK to update dependencies.
Step 3: Right click on the Master.xml file and select Run as  TestNG Suite 
* BaseClass.java contains the method to invoke the driver and to close it.
* TestCaseValidation.java contains the test cases to open the BeCognizant page and extract user information from the profile.
