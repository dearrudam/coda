### First, let's load the java sdk and change to the code repository:

`source "/root/.sdkman/bin/sdkman-init.sh"`{{exec}}

`cd java-hello-world-maven`{{exec}}

### Let's compile the project:

`mvn compile`{{exec}}

### Let's execute the project:

`mvn exec:java -Dexec.mainClass="br.soujava.collabtime.App"`{{exec}}

### Let's clean up the project:

`mvn clean`{{exec}}
