## Package the project into jar archive

```bash
mvn clean package
# run the project
mvn spring-boot:run -Dspring-boot.run.arguments=--spring.profiles.active=dev
```

Check the site [http://localhost:8081/actuator/health](http://localhost:8081/actuator/health)

You should see like this:
**{"status":"UP"}** in browser