# OrangeHRM Automation with Selenium and Java

This repository contains automated test scripts for the OrangeHRM application using Selenium WebDriver and Java. The purpose of this project is to provide a robust framework for testing the functionality of the OrangeHRM platform.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Tests](#tests)
- [Contributing](#contributing)

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Java JDK (version 8 or higher)
- Apache Maven
- An IDE (e.g., IntelliJ IDEA, Eclipse)
- ChromeDriver (or another WebDriver for your preferred browser)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/hasanazeerkhan/orangehrm-automation-selenium-java.git
   cd orangehrm-automation-selenium-java
   ```

2. **Build the project using Maven:**
   ```bash
   mvn clean install
   ```

3. **Download the appropriate WebDriver** for your browser and ensure it is in your system's PATH.

## Usage

To run the tests, use the following command:

```bash
mvn test
```

You can specify a particular test suite or test class using the `-Dtest` flag:

```bash
mvn -Dtest=YourTestClassName test
```

## Tests

This project includes various test cases for different functionalities of the OrangeHRM application. The tests can be found in the `src/test/java` directory. Each test is structured to validate a specific feature of the application.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create your feature branch `git checkout -b feature/AmazingFeature`
3. Commit your changes `git commit -m 'Add some AmazingFeature'`
4. Push to the branch `git push origin feature/AmazingFeature`
5. Open a pull request.

## Acknowledgements

- [Selenium](https://www.selenium.dev/)
- [OrangeHRM](https://www.orangehrm.com/)