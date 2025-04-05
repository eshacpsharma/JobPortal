# How to Run 

## Install Java 17 
- https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html
- JAVA_HOME to Env Variable 

## Maven 3.9.6 
(https://maven.apache.org/download.cgi)
- Add to PATH (bin folder)
- MAVEN_HOME

### Verify JAVA and MAVEN intallation 
```
# Java installation check
java -version
$env:JAVA_HOME

# Maven Installation check
mvn -version
$env:MAVEN_HOME

```

## Setup MYSQL DB 
- ULR : https://dev.mysql.com/downloads/installer/
- Web Install
- 123@password

```
# Create DB
CREATE DATABASE jobportal;
```

## Run 

- Give Error So Commented Test
```
mvn clean install
```

- Run Program 
- Go in Target Folder
```
java -jar .\Job_Search_Platform-0.0.1-SNAPSHOT.jar
```