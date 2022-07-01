# ea-july1
*Note: Instructions for IntelliJ*

**To Start Application:**
---
- `mvn clean install` to install modules
- enter your db details into *employeesdb.properties*
- ensure project is defined as maven project (if not, right click project name and convert to maven project)
- To run application run `java -jar target/JavaWebService-1.0-SNAPSHOT.jar server config.yml`
- To check if API is running, navigate to http://localhost:8080/swagger
- On another terminal navigate to Frontend folder and run `npm install` and `npm start`
