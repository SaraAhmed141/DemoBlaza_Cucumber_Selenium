
Web Automation Assessment
Project Overview
This project aims to automate user interactions with the STORE (demoblaze.com) website. The assessment involves verifying user signup, purchasing two products, and handling various validation checks. The project is implemented using Java, Selenium, TestNG, and Cucumber (BDD), following Java clean code guidelines.

Scenarios
Scenario 1: Verify User Signup
Navigate to STORE (demoblaze.com).
Sign Up:
Click on the "Sign up" button in the header.
Fill in the username and password in the sign-up form.
Validate that the success message "Sign up successful." is displayed.
Scenario 2: Verify Purchase of Two Products
Login:
Click on the "Login" button in the header.
Fill in the username and password in the login form.
Validate that the account opens successfully.
Select Products:
Click on "Laptops" in the categories on the home page.
Choose the first product and click on the "Add to cart" button.
Validate that the product is successfully added.
Choose the second product and click on the "Add to cart" button.
Validate that the product is successfully added.
Cart and Checkout:
Click on the "Cart" button in the header.
Validate that both products (including title and price) are listed in the cart.
Validate that the total amount is calculated correctly.
Click on the "Place Order" button.
Validate that the total amount is correct on the order page.
Fill in the details (Name, Country, City, Credit Card, Month, and Year).
Click on the "Purchase" button.
Validate that the message "Thank you for your purchase!" is displayed.
Negative Scenarios
Add your own negative scenarios to test the robustness of the application (e.g., invalid login, adding out-of-stock items to the cart, etc.).
Tools and Technologies
Java: Programming language used for writing the test scripts.
Selenium: WebDriver used for automating browser interactions.
TestNG: Testing framework for running the test cases.
Cucumber (BDD): Behavior-Driven Development framework for writing test cases in a readable format and add fake filler when fill the form
Extent/Allure Reports: Tools for generating detailed test execution reports.
Project Structure
src/main/java: Contains the main application code.
src/test/java: Contains the test scripts and step definitions.
src/test/resources: Contains the feature files for Cucumber scenarios.
reports: Directory where the test execution reports are stored.
Setup and Execution
Prerequisites
JDK (Java Development Kit)
Maven
An IDE (e.g., IntelliJ IDEA, Eclipse)
