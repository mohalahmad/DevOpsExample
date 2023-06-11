# DevOpsExample
To run this exapmle you need to have the below requirments installed in your machine:
  - java 
  - maven

To build this application firxt you need to run below command to packge and extract the jar file:
```
mvn clean install  -DskipTests
```
now you have your jar file in the **/target** dir

run below to start your REST API:
```
java -jar .\target\rest-0.0.1-SNAPSHOT.jar
```
