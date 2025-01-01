# FoodicsTask
For the 1st task
1. Set Up the Automation Framework
Framework Design
1.	Use a Testing Framework:
o	Use RestAssured for API testing due to its fluent interface and rich feature set.
o	TestNG for test execution and reporting.
o	Maven for dependency management.
o	Follow a structured approach to organize test cases, utilities, and configuration files.
2.	Configuration Management:
o	Externalize API base URLs and other configuration parameters using properties files or environment variables
     3. You will be working with the base url https://reqres.in to implement the following scenarios 
a. Create a User
•	Send a POST request to /api/users with a JSON payload containing user details (e.g., name, job, age).
•	Validate the response to ensure the user is created successfully.

b. Retrieve a User
•	Send a GET request to /api/users/{id} using the user ID from the creation step.
•	Validate that the returned information matches the created user details.
c. Update a User
•	Send a PUT request to /api/users/{id} with updated details.
•	Validate that the response confirms the update and that the changes are reflected
4. Implement Error Handling:
•	Ensure robust error handling for scenarios such as invalid requests, network failures, and unexpected responses.
•	Log detailed error messages for debugging.
5. Code Quality and Version Control:
•	Code Quality: Follow best practices for writing clean, maintainable, and reusable code.
•	Version Control: Use version control (e.g., Git) to manage your test scripts and provide access to your repository, Important Notes:Add a readme file which should be clear enough and the evaluator can easily install the project with all dependencies and run it successfully.

For the 2nd task
# RestAssured API Testing Project

This project contains automated API tests using **RestAssured** and **TestNG** for creating, retrieving, and updating a user in a RESTful API. The project is version-controlled using **Git** and is set up to run on **Maven**. 

## Prerequisites

Before you start, ensure you have the following installed on your system:

1. **Java 8+**  
   Download and install the latest version of Java from [Oracle](https://www.oracle.com/java/technologies/javase-jdk8-downloads.html) or use OpenJDK.

2. **Maven**  
   This project uses Maven for dependency management and building the project. You can download it from [here](https://maven.apache.org/download.cgi). After installation, verify by running:

   ```bash
   mvn -v
