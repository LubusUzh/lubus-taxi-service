# Taxi-service project
## Description
### A few words about this project:
This is a taxi service web application made on java. You can add a car, driver, manufacturer, also you can register a new driver and chose car for this driver.   

### Here are a few features of the Taxi-service project:
*Register a driver in the database*

*Login to the system*

*Register a car*

*Register a manufacturer*

*Add driver to the car*

*Get all cars by driver*

*Remove driver from the database*

*Remove car from the database*

*Remove manufacturer from the database*

### Project structure:
**This Taxi-service project based on an N-Tier Architecture:**

**DAO** - layer, that works with the DB.

**Service** - layer, where are all logic.

**Controller** - layer, that works with clients requests.

### Technologies:
Java 17

Apache Maven 3.8.0

Apache Tomcat 9.0.50

MySQL 8.0.30

Java Servlet API

### To run the Taxi-service project you need:
1. Make a fork of this project to your repository.
2. Copy link from your repository and create a new project in your IDE.
3. Write your data in the ConnectionUtil.class:
```
    private static final String URL = "Write URL to your database";
    private static final String USERNAME = "Write your username";
    private static final String PASSWORD = "Write your password";
    private static final String JDBC_DRIVER = "Write path to your JDBC driver";
```
4. Create your database using init_db.sql.
5. Install Tomcat 9.0.50.
6. Configure Tomcat Server.
7. Run your code.