
# EMS

## Table of Contents
- [Installation](#installation)
- [Clone the repository](#Clone_the_repository)
- [Access the application](#Access_the_application)

## Installation

### Clone the repository
To get started, clone the repository using the following command:
```bash
git clone https://github.com/Zakaria-MOKRAM/ems-backend.git 
```
After cloning, move to the project directory:<br>
```bash
cd ems backend
```
Install the required packages:<br>
```bash
mvn install
```
If you're using Gradle, use this command instead:
```bash
./gradlew build
```
This will download and install the required dependencies for the Spring Boot project.
Start the Spring Boot server:
```bash
mvn spring-boot:run
```
If you're using Gradle, run this command instead:
```bash
./gradlew bootRun
```
The application will now be running.
### Access the application
Once the server is running, open your browser and navigate to http://localhost:8080 to access the application.
