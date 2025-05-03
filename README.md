# Asana Automation Testing Framework

This project contains automated tests for Asana using Selenium WebDriver and Cucumber framework.

## Project Structure
```
src/
├── main/java/com/asana/test/
│   ├── pages/         # Page Object classes
│   └── utils/         # Utility classes
└── test/
    ├── java/com/asana/test/
    │   ├── runners/   # Test runners
    │   └── steps/     # Step definitions
    └── resources/
        └── features/  # Feature files
```

## Setup
1. Install Java 11 or higher
2. Install Maven
3. Clone this repository
4. Run `mvn clean install`

## Running Tests
```bash
mvn test
```

## Test Reports
Test reports are generated in the `target/cucumber-reports` directory after test execution.
