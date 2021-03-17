# Welcome to CS_6461 Illustrated Project (March, 2021)
This inspired project is based on Prof.Lancaster's course CSCI6461 Computer Architecture,
However, it is not recorded or graded any more because this project is shown with an illustrated demo,
neither for the study use nor for personal or business use due to the private issue.
This project can be a good base for people who interested with related area.

Please remembered to follow [GW Academic Integrity Code](https://studentconduct.gwu.edu/code-academic-integrity).

## Table of Contents

- For developers
  * [Notes](#notes)
  * [Contributing](#contributing)
  * [Usage](#usage)
  * [About Maven](#about-maven)
- [Contacts](#contacts)

## Notes

1. The project is managed by [Apache Maven](https://maven.apache.org/), 
it is highly recommend to use [Intellij IDEA Ultimate](https://www.jetbrains.com/idea/download/) (with built-in Maven v2 & v3 plugin, zero configuration).

2. As requested in [official course guide](http://www.mslcourses.com/CSCI6461Section11Spring2018/),
JDK 8+ should be used. The default compiler level has been set to 1.8 (JDK 1.8), please revise pom.xml
accordingly if you are using JDK 9.

3. The implementation of UI is powered by JavaFX, Idea has included a WYSIWYG layout editor in case you need one.

## Contributing
1. __Please do not commit anything but source code and resource files to this repository, also please make modifications based on the
latest version of code to avoid conflict.__
2. __Please do include a message for every commit.__
3. __Please inform all team members before commit any change regarding to pom.xml, .gitignore and simulator.iml.__ 

## Usage
Revise pom.xml if you are using JDK 9
```xml
<properties>
  <maven.compiler.source>9</maven.compiler.source>
  <maven.compiler.target>9</maven.compiler.target>
</properties>
```
Delete target folder
```sh
$ mvn clean
```
Build artifact
```sh
$ mvn install
```
Run / Debug
```sh
$ mvn verify
```
Run Unit Test
```sh
$ mvn test
```
## About Maven
<p align="center">
  <img src="https://cloud.githubusercontent.com/assets/300046/16313672/881e4a8e-3937-11e6-8af5-1c3b93b9caef.jpg">
</p>

## Contacts
- [Ziyue Li](mailto:zli51@gwu.edu) (a.k.a. David)
