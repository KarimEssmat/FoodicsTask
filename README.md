# FoodicsTask
For the 1st task
Automated Test Suite for Amazon Workflow
Overview
This project automates key functionalities of an e-commerce website, specifically Amazon. The test suite is designed using Selenium WebDriver and TestNG to validate core workflows, including login, product filtering, cart management, checkout, and logout.

Features Tested
Login Functionality

Logs into the application using valid credentials.
Verifies successful login.
Navigation to Video Games Section

Automates navigation to the Video Games section using menu interactions.
Product Filtering and Sorting

Applies filters such as free shipping and new condition.
Sorts products by price (high to low).
Adding Products to Cart

Identifies and adds products priced below a specified threshold (e.g., 15,000) to the cart.
Checkout Process

Proceeds to checkout and fills in address details.
Handles unexpected pop-ups or interruptions during the process.
Cart Management

Removes all products from the cart after checkout to ensure cart cleanliness.
Logout Functionality

Logs out of the application by hovering over the account menu and clicking the logout button.
How to Enhance the Tests
Data-Driven Testing

Use external data sources (e.g., Excel, CSV, JSON) to provide input for username, password, price threshold, and address details.
Cross-Browser Testing

Execute tests on different browsers (e.g., Firefox, Safari, Edge) to ensure compatibility.
Improved Exception Handling

Implement robust exception handling for network issues, dynamic element loading, and unexpected behavior.
Reporting

Integrate tools like Allure or Extent Reports for better test execution insights and reporting.
Parallel Execution

Use TestNG's parallel execution feature to run tests concurrently and reduce execution time.
Assertions

Add more validation points (e.g., verify product name and price in the cart, confirm order placement success).
Performance Testing

Measure page load times and responsiveness of various actions.
Additional Test Cases to Add
Negative Test Cases

Attempt login with invalid credentials.
Try to add an out-of-stock product to the cart.
Proceed to checkout without adding any products.
Search Functionality

Verify the search results for specific keywords.
Test advanced search filters and their combinations.
Payment Gateway Testing

Validate payment options like COD, credit cards, and wallets.
Test failed payment scenarios.
Order History Verification

Check if completed orders appear in the order history.
Wishlist Functionality

Add items to the wishlist and verify their presence.
Move items from the wishlist to the cart.
UI and UX Validation

Test the responsiveness of the site across different screen sizes.
Validate the alignment and visibility of critical elements.
Bulk Actions

Test adding multiple items to the cart and removing them.
Verify the correct calculation of the total cart amount.
How to Run the Tests
Prerequisites

Install Java JDK 8 or higher.
Install Maven for dependency management.
Install ChromeDriver and add it to your system PATH.
Setup

Clone this repository.
Run mvn clean install to download dependencies.
Execution

Run tests using TestNG by executing the testng.xml file or directly running RunTestCases class in your IDE.
Post-Test

Review the console output for results.
Check the reports directory (if configured) for detailed execution results.


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
