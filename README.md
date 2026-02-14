# Maven Lifecycle Explanation

## Clean Lifecycle
The Clean Lifecycle is responsible for cleaning the project.
It removes the target directory and compiled files.

Phases:
- pre-clean
- clean
- post-clean

Example:
mvn clean

Purpose:
To make the project fresh before rebuilding.


## Default Lifecycle
The Default Lifecycle handles the main build process.

Important Phases:
- validate
- compile
- test
- package
- verify
- install
- deploy

Example:
mvn compile
mvn package

Purpose:
To build, test, and package the application.
