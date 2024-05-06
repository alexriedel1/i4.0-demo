## Start Workflowmanager
- install Java JDK https://www.oracle.com/de/java/technologies/downloads/
- install maven https://maven.apache.org/
- create mysql database `activiti`
- build jar via `mvn clean compile assembly:single`
- run via: `java -cp target/workflowmanager-0.0.1-jar-with-dependencies.jar de.eahjena.wi.workflowmanager.App`

