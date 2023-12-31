# Selenium Test Automation Project - Saucedemo.com

This repository contains a Java project for automating tests using Selenium WebDriver, Maven, and TestNG to test the web application [Saucedemo](https://www.saucedemo.com/). The project follows the Page Object Model (POM) design pattern, providing a structured and maintainable framework for automating UI tests. The tests are categorized into the following sections:

- **Login Tests:** Verify user login functionality. https://github.com/link ***under construction****
- **Products Tests:** Test product selection and details.
- **Cart Tests:** Ensure correct product additions to the cart.
- **Checkout Tests:** Test the order checkout process.
- **Payment Tests:** Verify payment processing.

## Prerequisites

Before running the tests, ensure you have the following dependencies installed:

- Java Development Kit (JDK)
- Maven
- TestNG
- WebDriver compatible with your preferred browser (Chrome, Firefox, etc.)

## Test Reports

TestNG generates HTML reports that provide detailed information on test results. These reports can be found in the `test-output` directory.

## Page Objects

The project follows the Page Object Model (POM) design pattern. Page objects are located in the `src/main/java/pages` directory. You can extend or modify them to accommodate changes in the application.
