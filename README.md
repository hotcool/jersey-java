# Synopsis

This is a project on how to build a web application with jersey functions

# Installation

## Pre-requirements:
	* Java
	* Gradle
	* Tomcat

* Run "gradle clean build"
* Deploy war to tomcat directory "cp /build/libs/jersey-java-0.0.1.war _Catalina.base_/webapps"
* Restart tomcat
* Verify application by "curl localhost:8080/jersey-java-0.0.1/rest/cool"
* Print out "Got it!" in console