# Java Selenium Automation Framework

![Automation Framework](./Test Automation Framework Architecture.png)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Running Tests](#running-tests)
- [Reporting](#reporting)
- [Continuous Integration (CI/CD)](#continuous-integration-cicd)
- [API Testing](#api-testing)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Welcome to the Java Selenium Automation Framework README. This comprehensive guide provides details on setting up, configuring, and running the automation framework. It covers web automation using Selenium WebDriver, API testing with Rest Assured, test execution with JUnit 5, BDD scenarios with Cucumber, detailed logging, extensive reporting, and CI/CD integration with Jenkins.

## Features

- **Java 11**: The framework is written in Java, making it platform-independent.
- **Selenium 4**: Selenium is used for web automation, allowing you to interact with web applications.
- **JUnit 5**: JUnit 5 is used for test execution and assertions.
- **Cucumber**: Cucumber is used for behavior-driven development (BDD) and writing test scenarios in Gherkin syntax.
- **Logging**: Log4j is used for detailed logging to track test execution and debugging.
- **Reporting**: Extent Reports is integrated for comprehensive test reporting.
- **Screenshots**: Screenshots are captured and attached to reports for failed test cases.
- **Continuous Integration (CI/CD)**: Jenkins is configured for automated test execution on code commits.

## Prerequisites

Before getting started, ensure you have the following tools and dependencies installed:

- Java Development Kit (JDK)
- Selenium WebDriver 4.11.0
- JUnit 5
- Cucumber
- Log4j2
- Extent Reports
- Jenkins (for CI/CD)

For a detailed setup guide, refer to [Prerequisites and Setup](./docs/prerequisites-setup.md).

## Getting Started

Follow these steps to set up and run the automation framework:

1. Clone this repository to your local machine.
2. Configure your environment by installing the necessary tools and dependencies.
3. Set up WebDriver and ensure it's compatible with your browser.
4. Run the tests locally using your preferred IDE or the command line.

For detailed instructions, refer to [Getting Started](./docs/getting-started.md).

## Project Structure

The project is structured as follows:

- `src/main/java`: Contains utility classes and configuration.
- `src/test/java`: Contains test classes and step definitions.
- `src/test/resources`: Contains feature files for Cucumber scenarios.

For an in-depth overview, refer to [Project Structure](./docs/project-structure.md).

## Running Tests

To run the tests locally, use your preferred IDE or execute Maven commands. For example:

```shell
mvn clean test
‣敓敬楮浵弴番楮㕴䍟捵浵敢ੲ