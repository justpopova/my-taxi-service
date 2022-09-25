# TAXI SERVICE
**Features**
- registration
- authentication
- log in / log out
- create, update and remove models
- display all cars, drivers and manufacturers

**Project structure**

The project has N-Tier Architecture:
- DAO(data access object) - all work with database at DAO layer(CRUD)
- Service - all business logic based at service layer
- Controllers - 

**Technologies**
- JAVA 11
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
      picture of parameters
5. Create necessary tables in your database using the file init_db.sql.
6. Install Tomcat (https://tomcat.apache.org/download-90.cgi).
7. Add Tomcat server to sonfiguration and Fix it.
8. Run the project.
