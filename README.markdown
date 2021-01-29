# Maven Composites

| Branch | Status |
| ------ | ------ |
|Master|[![Build Status](https://img.shields.io/circleci/project/github/michaellasmanis/lasmanis-maven-composites/master.svg?style=flat)](https://circleci.com/gh/michaellasmanis/lasmanis-maven-composites/tree/master) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.lasmanis.maven.composites/composites-reactor/badge.svg?style=flat)](https://maven-badges.herokuapp.com/maven-central/com.lasmanis.maven.composites/composites-reactor)|


This project sets up groups of maven dependencies for Java projects.

## Dependencies Provided

* unit-test
    * junit:junit
    * org.assertj:assertj-core
    * org.mockito:mockito-core

## Usage

Below is the basic usage pattern for inclusion in a pom:

```xml
<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
    <dependencies>
        <dependency>
            <groupId>com.lasmanis.maven.composites</groupId>
            <artifactId>CHANGEME</artifactId>
            <version>CHANGEME</version>
        </dependency>
    </dependencies>
</project>
```
Make sure to set the artifactId and version of the composite to attach.  You can attach more than one composite to a project.
