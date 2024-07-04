# Config Service

This application is part of the Polar Bookshop system and provides a configuration server. It's part of the project
built in the [Cloud Native Spring in Action](https://www.manning.com/books/cloud-native-spring-in-action) book
by [Thomas Vitale](https://www.thomasvitale.com).

## Useful Commands

| Gradle Command                   | Description                                   |
|:---------------------------------|:----------------------------------------------|
| `./mvnw spring-boot:run`         | Run the application.                          |
| `./mvnw package`                 | Build the application.                        |
| `./mvnw test`                    | Run tests.                                    |
| `./mvnw spring-boot:repackage`   | Package the application as a JAR.             |
| `./mvnw spring-boot:build-image` | Package the application as a container image. |

After building the application, you can also run it from the Java CLI:

```bash
java -jar ./target/config-service-0.0.1-SNAPSHOT.jar
```