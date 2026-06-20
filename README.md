# Platione QA Automation Framework

## Overview

This project demonstrates a scalable QA Automation Framework built using Playwright and TypeScript. The framework is designed to support UI testing, API testing, test data management, and future scalability requirements.

## Framework Architecture

The framework follows the following design patterns:

* Page Object Model (POM)
* API Client Pattern
* Factory Pattern
* Utility Pattern

## Folder Structure

PLATIONE-QA-FRAMEWORK
│
├── api
│   ├── clients
│   ├── builders
│   ├── validators
│   └── auth
│
├── pages
│
├── components
│
├── data
│   ├── factories
│   ├── seeders
│   └── json
│
├── utils
│
├── environments
│
├── tests
│   ├── api
│   └── ui
│
└── README.md
```

## Test Data Strategy

The framework supports reusable and dynamic test data generation using the Factory Pattern.

### Supported Test Data

* Hot Lead
* Cold Lead
* Duplicate Contact
* Dynamic User Data

## API Testing Strategy

API automation is implemented using Playwright APIRequestContext.

Features:

* GET Requests
* POST Requests
* Response Validation
* Status Code Validation
* Data Verification

## UI Testing Strategy

The framework uses the Page Object Model to improve maintainability and reusability.

Benefits:

* Reduced code duplication
* Easy maintenance
* Better readability
* Scalable automation architecture

## Utility Layer

Utility classes provide:

* Logging
* Screenshot Capture
* Configuration Management
* Common Reusable Functions

## Environment Management

Supported Environments:

* QA
* Staging
* Production

Environment-specific configurations can be maintained using environment files.

## Scalability Approach

### Small Suite (3 Tests)

* Sequential execution

### Medium Suite (50 Tests)

* Parallel execution
* Shared utilities
* Modular page objects

### Large Suite (500+ Tests)

* CI/CD integration
* Distributed execution
* Containerized execution
* Advanced reporting

## Technologies Used

* Playwright
* TypeScript
* Node.js
* Git
* GitHub

## Future Enhancements

* Allure Reporting
* Database Validation
* Docker Integration
* Jenkins/GitHub Actions Integration
* Cross-browser Execution

## Author

Surekha Kolekar
Software Testing (QA Automation) Internship Assignment
