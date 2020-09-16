# Basics

( https://www.youtube.com/playlist?list=PLGibysfsUS7NAbefiaj1V4LbX0glTftDI )

## Setup

File -> new -> new Maven Project -> org.apache.maven.archetypes:maven-archetype-simple

From https://mvnrepository.com/ , put the corresponding dependency into the `pom.xml` file

```xml
<!-- https://mvnrepository.com/artifact/org.springframework/spring-context -->
<dependency>
    <groupId>org.springframework</groupId>
    <artifactId>spring-context</artifactId>
    <version>5.2.9.RELEASE</version>
</dependency>
```

![](https://raw.githubusercontent.com/Ruslan-Aliyev/Spring-Lesson/master/Illustrations/create_simple_spring_proj.PNG)

The resulting project structure should be like below:

![](https://raw.githubusercontent.com/Ruslan-Aliyev/Spring-Lesson/master/Illustrations/simple_proj_structure.PNG)

## Most simple example

Asking Spring to create object

![](https://raw.githubusercontent.com/Ruslan-Aliyev/Spring-Lesson/master/Illustrations/most_basic_example.PNG)

