# Selenium Docker Runner

This repository contains the **Jenkinsfile** and **Docker Compose** configurations required to run the Selenium tests from the [selenium-docker](https://github.com/Moh88CS/selenium-docker) repository. It sets up the infrastructure for distributed testing using **Jenkins**, **Docker**, and **Selenium Grid** across an **AWS EC2 fleet**.

## Key Features

- **Jenkins Pipeline**: Automates the execution of Selenium tests in a CI/CD pipeline.
- **Dockerized Selenium Grid**: Uses Docker to set up Selenium Grid for cross-browser testing.
- **AWS EC2 Integration**: Distributes tests across multiple EC2 instances for scalability.
- **Docker Compose**: Simplifies the setup of Selenium Grid and test execution environments.

## Prerequisites

Before you begin, ensure you have the following installed:

- **Docker**: For containerizing the testing environment.
- **Jenkins**: For CI/CD pipeline automation.
- **AWS EC2 Instances**: For distributed test execution.
- **Git**: To clone the repository.

## Setup Instructions (Made to run on AWS cloud machines via script)

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Moh88CS/selenium-docker-runner.git
   cd selenium-docker-runner
   docker-compose up -d

