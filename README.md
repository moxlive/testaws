# Test AWS Setup

## Sample dropwizard code
   * [link](https://www.dropwizard.io/en/latest/getting-started.html)
   * Commands:
     1. Copy hello-world.yml to jar folder(target)
     2. Generate fat jar: ```mvn package```
     3. Run shade plugin to download include all dependency: ```mvn package shade:shade```
     3. Start the server ```java -jar target/hello-world-1.0-SNAPSHOT.jar server hello-world.yml```
