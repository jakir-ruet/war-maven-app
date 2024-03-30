### Welcome to War-Maven-App
This is DevOps testing purpose application

Create App with vscode
- Create Java Project
- Maven create from archetype
- maven-archetype-webapp
- Select version (1.4)
- Give Group ID (com.mavenapp)
- Give Artifact ID (mavenapp)
- Choose the destination directory
- Open app

Build
```bash
mvn initialize
```
Test
```bash
mvn test
```
Validation
```bash
mvn validate 
```
[More Command](https://maven.apache.org/run.html)

Let me check
```bash
http://192.168.162.130:8080/mavenapp/
```
