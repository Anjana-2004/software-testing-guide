# Software Testing Guide

This repository is a comprehensive, step-by-step learning resource for **Software Testing** using both **Manual Testing** and **Selenium IDE-based Automation Testing**. The aim is to provide structured examples and practical testing scenarios to help learners understand the process, apply the knowledge, and build confidence in web testing.

---

## Table of Contents
- [Introduction to Software Testing](#introduction-to-software-testing)
- [Manual Testing Example - OpenCart](#manual-testing-example---opencart)
- [Introduction to Selenium IDE](#introduction-to-selenium-ide)
- [Selenium IDE Example - PHPTravels](#selenium-ide-example---phptravels)
- [Selenium WebDriver Script](#selenium-webdriver-script)
- [Project Structure](#project-structure)
- [Additional Resources](#additional-resources)
- [Conclusion](#conclusion)

---

## Introduction to Software Testing

Software testing is a critical part of the software development lifecycle that ensures the quality, reliability, and performance of software applications. It is the process of systematically verifying whether a product meets the expected requirements and identifying any defects before the product is released.

### Why Software Testing is Important
- Detects bugs and errors early, reducing development costs.
- Ensures the software meets user requirements.
- Improves product quality and enhances customer satisfaction.
- Helps maintain the stability and security of the application.

### Benefits of Software Testing
- **Improved Quality:** Ensures that software works as intended in different scenarios.
- **Increased Confidence:** Builds trust in the application’s performance.
- **Better User Experience:** Helps in delivering a smoother and more reliable product.
- **Risk Mitigation:** Identifies critical failures before deployment.

### Scope for Continuous Improvement
Software testing is an ongoing process that can always be refined by:
- Writing more comprehensive test cases.
- Including edge cases and complex user behaviors.
- Updating tests as new features are added.
- Incorporating advanced automation tools for efficiency.

---

## Manual Testing Example - OpenCart

### Application Under Test:
[OpenCart Demo Website](https://demo.opencart.com/)

Manual testing is performed step-by-step by a human without using automation tools. It focuses on validating UI, navigation, input fields, and functional workflows.

### Test Case Document:
- [ManualTesting_OpenCart.xlsx](./ManualTesting_OpenCart.xlsx)

This file contains **25 carefully designed test cases** covering:
- Homepage navigation
- Product search
- Add to cart functionality
- Checkout process
- Handling invalid inputs

The test cases are structured to verify real user scenarios on the OpenCart demo website.

---

## Introduction to Selenium IDE

Selenium IDE is a browser-based automation tool that allows testers to record, edit, and playback interactions with web applications. It is especially useful for beginners as no programming is required.

### Key Features:
- Record and playback browser actions.
- Export tests to Python, Java, and other languages.
- Build and execute test suites.
- Simple, user-friendly interface.

### Other Popular Automation Tools:
- **Selenium WebDriver:** Script-based browser automation.
- **Cypress:** Modern front-end testing framework.
- **Katalon Studio:** All-in-one web, API, and mobile testing platform.

---

## Selenium IDE Example - PHPTravels

### Application Under Test:
[PHPTravels Demo Website](https://phptravels.net/)

### Selenium IDE Project:
- [phptravels_flight_booking.side](./SeleniumIDEProjects/phptravels_flight_booking.side)

This Selenium IDE project demonstrates a full test scenario:
- Searching for flights
- Navigating to hotel bookings
- Completing a hotel booking form

### How to Run:
1. Install the Selenium IDE browser extension (Chrome or Firefox).
2. Load the `.side` project file in Selenium IDE.
3. Execute the test by clicking **Play Current Test Case**.

This practical example helps in understanding how Selenium IDE can be used for automating real-world user flows.

---

## Selenium WebDriver Script

A Python Selenium WebDriver script is also provided for users who wish to go beyond Selenium IDE and explore code-based automation.

- [test_phptravels.py](./SeleniumWebDriverScripts/test_phptravels.py)

This script automates the same booking process from the Selenium IDE project using Python and Selenium WebDriver, allowing for more detailed control, validation, and customization in the automation workflow.

---

## Project Structure

```text
software-testing-guide/
│
├── README.md                   # Detailed testing guide
├── ManualTesting_OpenCart.xlsx # 25 manual test cases for OpenCart
├── SeleniumIDEProjects/        # Selenium IDE project files (.side)
│   └── phptravels_flight_booking.side
├── SeleniumWebDriverScripts/   # Python Selenium WebDriver script
│   └── test_phptravels.py
├── Screenshots/                # (Optional) Screenshots of test execution steps
├── Resources/                  # Additional learning references and documentation
│   └── Resources.md

