## Prerequisites

 - JDK 1.9 or later



## Build
from project root folder
### Linux/Mac
 - ./mvnw clean install
 
### Windows
 - ./mvnw.cmd clean install
 
## Run
java -Dexecution.path=${blackbox executable path} -jar target/bigpanda-0.1.0.jar 

you can find output by url http://localhost:8080/statistics

 
## Things to improve
 - Add more test
 - Logging
 - Exception handling


