# Http Client Demo

In this tutorial you will learn how to use the HttpClient in Java 11 to perform a GET request to a local server.

## Running this application

Before running the Java application you will need to go into the server folder and `npm i` to install the `json-server` dependency. Next, run `npm start` and if the local server starts up on port 3000 you are ready to go.

## Running the Java Application

mvn clean compile assembly:single

java -jar target/java -jar target/client-1.0-SNAPSHOT-jar-with-dependencies.jar
