# CSE2522 – Software Testing and Validation (Assignment 02)

University of Sri Jayewardenepura
Faculty of Computing
Bachelor of Computing (Honours) in Software Engineering


## Project Overview

This project contains **automated test scripts** developed for the **UITesting Playground** web application. The automation is implemented using **Selenium WebDriver** and **NUnit** in C#.

The project follows the **Page Object Model (POM)** design pattern to ensure **maintainability** and **scalability**.

The goal of this assignment is to verify the **functionality of different pages and features** of the UITesting Playground site based on the provided test cases.



## Tools and Technologies

* Programming Language: C# (.NET)
* Automation Tool:Selenium WebDriver
* Testing Framework: NUnit
* Design Pattern: Page Object Model (POM)
* IDE: Visual Studio
* Browser: Google Chrome (ChromeDriver)
* Version Control:Git & GitHub

---

## Project Structure

CSE2522_Assignment02/
├── Base/
│   └── TestBase.cs                 # Initializes WebDriver and handles setup/teardown
├── Pages/
│   ├── AlertsPage.cs               # Page Object for Alerts page
│   ├── ClickPage.cs                # Page Object for Click button page
│   ├── DynamicallyGeneratedPage.cs # Page Object for Dynamically Loaded page
│   ├── HomePage.cs                 # Page Object for Home page
│   ├── SampleAppPage.cs            # Page Object for Sample App page
│   └── TextInputPage.cs            # Page Object for Text Input page
└── Tests/
    ├── AlertsTests.cs              # Test cases for Alerts page
    ├── ClickTests.cs               # Test cases for Click button page
    ├── DynamicallyGeneratedTests.cs# Test cases for Dynamically Loaded page
    ├── SampleAppTests.cs           # Test cases for Sample App page
    └── TextInputTests.cs           # Test cases for Text Input page

---

## Test Cases Covered

1. **Text Input Page**

   * Verify page elements are displayed
   * Verify button text changes according to user input

2. **Sample App**

   * Successful login
   * Unsuccessful login
   * Page element verification

3. **Client Side Delay**

   * Trigger client-side data calculation via button
   * Verify loading indicator and result banner

4. **Alerts**

   * Alert, Confirm, and Prompt functionality
   * Verify alert messages and user interactions

5. **Click Button**

   * Verify click actions and counter updates

6. **Dynamically Loaded Page**

   * Verify content loaded after a delay

---

## How to Run Tests

1. **Clone the repository**:


git clone https://github.com/Maneesha121/CSE2522_Assignment02.git


2. **Open the project** in **Visual Studio**.

3. **Install required NuGet packages** (if not already installed):

   * Selenium.WebDriver
   * Selenium.WebDriver.ChromeDriver
   * NUnit
   * NUnit3TestAdapter
   * Selenium.Support

4. **Build the solution**.

5. **Run tests** using **Test Explorer** in Visual Studio or from the command line:


dotnet test


## Notes

* Tests are designed to run on **Google Chrome**. Ensure Chrome is installed.
* The project uses **Page Object Model (POM)** for **readability** and **maintainability**.
## Repository Link

[https://github.com/Maneesha121/CSE2522_Assignment02](https://github.com/Maneesha121/CSE2522_Assignment02)

