Run below for testing sampel app


```
mvn clean
mvn packahe -DskipTests=true
java --illegal-access=permit -jar target/helidon-jpa.jar


#Open a new command prompt

curl localhost:8080/example/response/Marco
```