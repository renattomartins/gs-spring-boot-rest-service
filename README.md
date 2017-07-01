# gs-spring-boot-rest-service
This is a simple repository for future reference about how to build a RESTful Web Service with Spring Boot.

It was based in [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/) tutorial.

### Instructions to run the application
1. Clone this repository
2. So, you must choose **one** of the four alternatives bellow to build and run the application:
    1. Alternative 1: If you prefer to use Gradle, run the command `./gradlew bootRun` on root folder
    2. Alternative 2: Or you can build the JAR file using `./gradlew build` and then running the JAR file<br /> `java -jar build/libs/gs-spring-boot-rest-service-0.1.0.jar`
    3. Alternative 3: If you prefer to use Maven, run the command `./mvnw spring-boot:run` also on root folder
    4. Alternative 4: Or you can yet build the JAR file using `./mvnw clean package` and then running the JAR file<br /> `java -jar target/gs-spring-boot-rest-service-0.1.0.jar`
3. After this, the service is up. If you visit http://localhost:8080/greeting you can see:
```javascript
 {"id": 1, "content": "Hello, World!"}
```

### About development environment

- Java 1.8.0_25
- Spring Boot 1.5.2
- Gradle 4.0
- Groovy 2.4.11
- Gradle Wrapper 2.13
- Ant 1.9.6
- Apanche Maven 3.5.0
- POM Model 4.0.0
- Takari Maven Wrapper 0.1.5
- Mac OS 10.12.5 x86_64
- Eclipse IDE Neon 4.6.3
- Atom 1.18.0 x64
- Git 2.8.1
- Tower 2.4.0 for OSx

## Some other details

### Used annotation
- @RestController
- @RequestMapping
- @RequestParam
- @SpringBootApplication

#### Related annotation
- @Controller
- @ResponseBody
- @Configuration
- @EnableAutoConfiguration
- @EnableWebMvc
- @ComponentScan
