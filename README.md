# Activity-API-Test

This repository contains automated API tests for the provided task.

## Pre-requisites

- Java 11+
- Rest Assured 5.5.0
- Apache Maven
- TestNG

## Running tests locally
To run test locally, right click inside the testng.xml file and press the green run icon


#### Clone this repository
```bash 
git clone git@github.com:Sylvestre01/Activity-API-Test-RestAssured.git
```

#### navigate to the project directory
```bash
cd Activity-API-Test-RestAssured
```

#### Install dependencies
```bash
mvn install
```

#### Run test
<!-- Describe that the command below will run the test, generate report and open it on the browsers -->
To run the tests, run the following command. This command will run the tests, generate a report and open it on the browser.

```bash
mvn test
```

### Generate report
<!-- Describe the use of playwright reporting. -->
I used the default playwright reporting to generate a report after running the tests. To generate the report, run the following command after running the tests.

```bash
mvn clean test
```

The report will be saved in the `/reports` directory.




## Running tests in Github CI/CD
The CI/CD pipeline is configured in the `.github/workflow/maven.yml` file to run the automated test on GitHub using the Docker container runner.

To run the tests in GitHub CI/CD, push the code to the repository and the pipeline will be triggered automatically.




## Authors
| 👤 Name        | Github                                         | LinkedIn                                                   |
|----------------|------------------------------------------------|------------------------------------------------------------|
| Sylvester Udoh | [@Sylvestre01](https://github.com/Sylvestre01) |[@SylvesterUdoh](https://www.linkedin.com/in/sylvester-udoh/) |

## 🤝 Contributing
Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/Sylvestre01/Activity-API-Test-RestAssured/issues).

## Show your support
Give a ⭐️ if you like this project!

## Acknowledgments
- [RestAssured](https://rest-assured.io/)
- [GitHub CI/CD](https://docs.github.com/ee/ci/)
- [Docker](https://www.docker.com/)
- [Java](https://www.java.com/en/)
- [TestNG](https://testng.org/)
- [Maven](https://maven.apache.org/)