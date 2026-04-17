```sh
mvn compile package
java -agentlib:jdwp=transport=dt_socket,server=y,suspend=y,address=:5005 -jar target/MIST_-2.1-jar-with-dependencies.jar
# Debug in VSCode
```
