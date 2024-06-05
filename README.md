
Java-Maven Build: Hello World

## Overview

This project is a simple Java application created using Maven. The application includes a basic "Hello World" program and associated unit tests.


## Project Setup

### Step 1: Generating the Project

First, create a directory for the project and navigate into it.

```bash
mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false
`````
- groupId: The group identifier for the project, typically a reversed domain name.
- artifactId: The name of the project.
- archetypeArtifactId: Specifies the archetype to use; maven-archetype-quickstart is a basic Java project template.
- archetypeVersion: The version of the archetype to use.
- interactiveMode: Setting this to false makes the command non-interactive.

![Screenshot 2024-06-05 034732](https://github.com/shivxm03/java-maven-greeting-app/assets/157244434/017184da-4e62-48d3-aac9-97d80a5e4398)

### Step 2: Navigating to the Project Directory

After the project is generated, change into the newly created project directory:

```bash
cd my-app
`````
### Step 3: Building the Project

Compile and packaging the project into a JAR file, run the following Maven command:
```bash
mvn package
`````
Output: 

![Screenshot 2024-06-05 034936](https://github.com/shivxm03/java-maven-greeting-app/assets/157244434/80c5b7bf-2e6f-41d4-bbee-71f10203428e)

### Step 4: Running the Application

```bash
java -cp target/my-app-1.0-SNAPSHOT.jar com.mycompany.app.App
`````
## Result

![Screenshot 2024-06-05 035001](https://github.com/shivxm03/java-maven-greeting-app/assets/157244434/bfc4b82e-6728-4032-b85b-c2126bcd4325)




