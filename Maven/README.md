# Maven

**Maven is an automation and Project Management tool developed by apache software foundation. It is based on POM.xml(Project Object Model).**
- Maven can build any number of projects into desired output such as .jar, .war, metadata.
- Mostly used for Java based projects.
- It was initially released on 13 July 2004.
- Maven is written in Java.
- Meaning of Maven is "Accumulator of Knowledge"
- Maven helps in getting the right Jar file for each project on these may be different version of separate packages.
- To download dependencies it is no more needed to visit the official website of each software. It could now be easily done by visiting.
- [mvnrepository](https://mvnrepository.com/)

**Dependencies:** It refers to the java libraries that are needed for the project.

**Repositories:** Refers to the directories of packaged jar files.

**Java Build Tool:** Ant, Maven, Gradle

# Problem Without Maven

**1) Adding set of jars in each project:** In case of struts, spring, we need to add jar files in each project It must include all the dependencies of jars also.

**2) Creating the right project structure:** We must create the right project structure in servlet, struts etc, otherwiseit will not be executed.

**3) Building and depending the project:** We must have to build and deploy the project so that it may work.

# What Maven Does?

1) It makes a project easy to build
2) It provides project information
3) Easy to add new dependencies,
    Therefore for Apache Maven helps to Manage
   - Build
   - Dependencies
   - Reports
   - Release
   - Distribution

# POM(Project Object Maven)
 
 - POM refers the the XML files that have all the information regarding project and configuration details.
 - Main configure file is pom.xml
 - It has the description of the project details regarding the versioning and configuration management of the project.
 - The XML files is the project home directory.

 POM.xml Contains:
 - Metadata
 - Dependencies
 - Kind of projects
 - Kind of Output (.jar, .war)
 - Description

**One Project -> One Workspace -> One pom.xml**

**Requirement for Build**
- Source Code(Present in Workspace)
- Compiler(Remote repo -> local repo -> workspace)
- Dependencies(Remote repo -> local repo -> workspace)

# Maven Architecture

![Maven-Architecture](https://github.com/herrry107/Jenkins/blob/main/images/maven-architecture.png)

**Local Repository:** Local repository refers to the machine of the developer where all the project Material is saved.

**Remote Repository:** It refers to the repository present on a webserver which is used when Maven needs to download dependencies. This repository works same as the central Repo whenever anything is needed from remote repository it is fact downloaded to the local repo and then it is used.

**Central Repository:** Central repository refers to the Maven community that comes into action when there is a need of dependencies and those dependencies cannot be found in the local repository.

**Maven Build Life Cycle Goals**
1) Generate Resource(Dependencies)
2) Compile code
3) Unit test
4) Package(Build)
5) Install(into local repo & artifactory)
6) Deploy(to server)
7) clean(delete all run time files): like **mvn install** and **mvn clean package**

- Build life cycle consists of a sequence of build phase and each build phase consist of a sequence of goals.
- Each goal is responsible for a particular tasks.
- When a phase is run all the goals related to that phase and its plugin are also compiled.

# ANT vs MAVEN

**ANT**

ANT does not has formal conventions, so we need to provide information of the project structure in build.xml file
- ANT is procedural, you need to provide info about what to do and when to do through code.
- There is no lifecyle in ANT.
- Is is a tool box.
- It is mainly a build tool.
- It is less preferred than Maven.

**Maven**

Maven has a convention to place source code, compiled code etc. So we don't need to provide information about the project structure in pom.xml file.
- Maven is declarative everything you define in the pom.xml file
- This is a lifecycle in Maven.
- It is a framework.
- It is mainly a project management tool.
- It is more preferred.
