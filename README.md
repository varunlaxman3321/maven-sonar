# SonarQube Maven Demo

Simple Java Maven project for demonstrating Maven build + SonarQube analysis.

## Requirements

- Java 17
- Maven
- SonarQube running on http://localhost:9000

## Run build + SonarQube analysis

mvn clean verify sonar:sonar

If SonarQube authentication is enabled:

mvn clean verify sonar:sonar -Dsonar.token=YOUR_SONAR_TOKEN

## SonarQube configuration

The SonarQube server URL and project details are configured in pom.xml.
