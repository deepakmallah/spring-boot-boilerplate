# spring-boot-boilerplate

**Technologies Used**
1. Java 11
2. Spring 5.1.8.RELEASE
3. Spring Boot 2.1.6.RELEASE
4. Gradle 5.6
5. MySQL 5.7

**Steps to Build and Start**

1. Generate gradle wrapper files `gradle wrapper`
2. Build artifacts `./gradlew build`
3. Start spring boot `java -jar build/libs/gs-spring-boot-0.1.0.jar`

Above commands can be run individually or in one go by `sh build-run.sh`

**End Points**
1. #### Add : Add user details like name and email
    
    End point : `http://localhost:8080/user/add`
    
    Method : POST
    
    Params : name & email
    
2. #### List All : Lists all the users

    End point : `http://localhost:8080/user/all`
    
    Method : GET
    
3. #### Get By Id : find User by Id

    End point : `http://localhost:8080/user/byId`
    
    Method : POST
    
    Params : id