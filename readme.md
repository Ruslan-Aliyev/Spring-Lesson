# Spring MVC

## Tutorials

- Basics theory: https://www.youtube.com/playlist?list=PLGibysfsUS7NAbefiaj1V4LbX0glTftDI 
- Getting started: https://www.youtube.com/playlist?list=PLsyeobzWxl7rFkYFysfTwBu1JBPaNNDrk 
- Spring MVC: 
	- https://www.youtube.com/watch?v=g2b-NbR48Jo
		- https://www.youtube.com/playlist?list=PLsyeobzWxl7rjSO6xX00UWmVhL90i-cOk
	- https://www.javatpoint.com/spring-mvc-tutorial
		- https://www.javatpoint.com/spring-mvc-crud-example
- Spring boot: https://www.youtube.com/playlist?list=PLsyeobzWxl7oA8QOlMtQsRT_I7Rx2hoX4 

## Basics: 

https://github.com/Ruslan-Aliyev/Spring-Lesson/blob/master/theory.md

## Setup

1. File -> new -> new Maven Project -> org.apache.maven.archetypes:maven-archetype-webapp

2. From https://mvnrepository.com/ , put the corresponding dependency into the `pom.xml` file

```xml
<!-- https://mvnrepository.com/artifact/org.springframework/spring-webmvc -->
<dependency>
    <groupId>org.springframework</groupId>
    <artifactId>spring-webmvc</artifactId>
    <version>5.2.9.RELEASE</version>
</dependency>

```

![](https://raw.githubusercontent.com/Ruslan-Aliyev/Spring-Lesson/master/Illustrations/create_spring_mvc_proj.PNG)

3. Link in Tomcat server by right click project in the left-hand-side project explorer -> properties -> targeted runtimes -> new -> select the latest Tomcat (now is v9.0) -> next -> browse and select installation directory.

The installation directory should be the unzipped folder from https://tomcat.apache.org/download-90.cgi

![](https://raw.githubusercontent.com/Ruslan-Aliyev/Spring-Lesson/master/Illustrations/tomcat.PNG)

## Architecture

![](https://raw.githubusercontent.com/Ruslan-Aliyev/Spring-Lesson/master/Illustrations/archi.PNG)
