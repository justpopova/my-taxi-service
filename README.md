# TAXI SERVICE
**Features**
- registration
- log in / log out
- create, update and remove cars/manufacturers/drivers
- display all cars, drivers and manufacturers

**Project structure**

The project has N-Tier Architecture:
- DAO(data access object) - all work with database at DAO layer(CRUD)
- Service - all business logic based at service layer
- Controllers - accept requests from the clients and send responses

**Technologies**
- Java 11
- JDBC
- MySQL
- Tomcat
- JSP
- Maven

**Instruction to run the project**
1. Fork this repository.
2. Copy link of project.
3. Create new project from VCS.
4. Edit ConnectionUtil.class - set necessary parameters:
```diff 
   private static final String URL = "URL";
   private static final String USERNAME = "USER NAME";
   private static final String PASSWORD = "PASSWORD";
   private static final String JDBC_DRIVER = "JDBC DRIVER";
```
For Example:
```diff
private static final String URL = "jdbc:mysql://localhost:3306/taxi";
private static final String USERNAME = "root";
private static final String PASSWORD = "9691";
private static final String JDBC_DRIVER = "com.mysql.cj.jdbc.Driver";
```
5. Create necessary tables in your database using the file init_db.sql.
6. Install Tomcat (https://tomcat.apache.org/download-90.cgi).
7. Configure Tomcat Server in your IDEA.
8. Run the project.
