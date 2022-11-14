# Test AWS Setup

## Sample dropwizard code
   * [link](https://www.dropwizard.io/en/latest/getting-started.html)
   * Commands:
     1. Copy hello-world.yml to jar folder(target)
     2. Generate fat jar: ```mvn package```
     3. Run shade plugin to download include all dependency: ```mvn package shade:shade```
     3. Start the server ```java -jar target/hello-world-1.0-SNAPSHOT.jar server hello-world.yml```

## Docker
   * Build
     1. ```docker build -t imagename .```
     
   * Run
     1. ```docker run -p 8080–8081:8080–8081 -it imagetag```
     
   * Images

     1. list images ```docker image```
     2. Delete images ```docker image rm imagename```
     
   * Container
     1. list all containers ```docker container ls -a```
     2. rm ALL containers ```docker container rm $(docker ps -aq)```
