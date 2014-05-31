restx-singlejar
===============


RESTX example to package app as a single executable jar.

## Build

`mvn package`

## Run

`java -jar target/singlejar-0.1-SNAPSHOT.jar`

Then check:

http://localhost:8080/ for static assets located in `src/main/resources/assets`.
http://localhost:8080/@/ui/ for RESTX console.
