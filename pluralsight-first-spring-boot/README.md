### First Spring Boot project created
#### Course from Pluralsight - Creating Your First Spring Boot Application

Command to run the project on port 8080
```bash
$ mvn spring-boot:run
```

Command to run the project with test configuration on port 9090
```bash
$ mvn spring-boot:run -Dspring.profiles.active=test
```
The 'test' part comes from the value placed in the /main/resources/application-test.properties filename

Command to run the project with production configuration on port 80(if access too)
```bash
$ mvn spring-boot:run -Dspring.profiles.active=prod
```
The 'prod' part comes from the value placed in the /main/resources/application-prod.properties filename