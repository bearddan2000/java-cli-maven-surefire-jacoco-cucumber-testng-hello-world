# java-cli-maven-surefire-jacoco-cucumber-testng-hello-world

## Description
A POC for maven app using testNg
and cucumber framework with jacoco
and surefire plugins.

## Tech stack
- java
- maven
  - testNg
  - surefire
  - jacoco
  - cucumber

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- jacoco report under bin/target/site/jacoco

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code concept] (https://stackoverflow.com/questions/67847818/maven-junit-5-cucumber-not-running-tests)
- [Jacoco config] (https://www.baeldung.com/jacoco)
