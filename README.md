# Project Title: Test Automation with Ruby

## Overview
This project is aimed at studying and implementing test automation using Ruby. It leverages several Ruby gems and libraries to facilitate the automation process and ensure efficient and reliable testing.

## Dependencies
To run the automation tests, the following dependencies are required:

- **Cucumber** (version 8.0): Cucumber is responsible for documenting test automation using Gherkin, a human-readable language that promotes collaboration between stakeholders and developers.

- **Capybara** (version 3.39.1 or later): Capybara provides support for performing test automation by simulating user interactions with web applications. It offers a simple and expressive API for automating web browsers.

- **Selenium WebDriver** (version 4.9.1 or later): Selenium WebDriver is a widely used tool for automating web browsers. It allows you to control browsers programmatically and interact with web elements on the page.

- **RSpec** (version 3.12): RSpec is a testing framework for Ruby that provides a domain-specific language (DSL) for writing test assertions. It enables you to define tests, specify expected outcomes, and verify the behavior of your code.

- **SitePrism** (version 4.0.2 or later): SitePrism is a framework for defining page objects in Ruby. It helps organize and maintain the elements and actions on web pages, making test automation more structured and readable.

## Getting Started
To get started with this project, follow these steps:

1. Ensure you have Ruby installed on your system. You can check the Ruby installation by running the following command in your terminal:

ruby --version


2. Clone the project repository from GitHub:

git clone <repository_url>

3. Navigate to the project directory:

cd <project_directory>

4. Install the required gems and dependencies using Bundler:

bundle install


5. Start writing your test scenarios in Gherkin syntax using Cucumber. You can find the feature files in the `features` directory.

6. Implement the step definitions for your scenarios using Ruby code. You can find the step definition files in the `features/step_definitions` directory.

7. Use Capybara and Selenium WebDriver to interact with web elements and perform actions in your tests. You can find examples and documentation on the Capybara and Selenium websites.

8. Write assertions using RSpec to validate the expected behavior of your application. You can define assertions in the step definition files or separate files dedicated to assertions.

9. Leverage SitePrism to define page objects and organize your test automation code. Create page object classes in the `features/support` directory and use them in your step definitions.

10. Run your tests using Cucumber and RSpec. Use the following command to execute all the tests:
 ```
 cucumber
 ```


