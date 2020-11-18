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

## Setter injection

![](https://raw.githubusercontent.com/Ruslan-Aliyev/Spring-Lesson/master/Illustrations/setter_inj.PNG)

## Constructor injection

![](https://raw.githubusercontent.com/Ruslan-Aliyev/Spring-Lesson/master/Illustrations/constr_inj.PNG)

## Injecting objects

![](https://raw.githubusercontent.com/Ruslan-Aliyev/Spring-Lesson/master/Illustrations/inj_obj.PNG)

## Injecting objects to collection (list)

![](https://raw.githubusercontent.com/Ruslan-Aliyev/Spring-Lesson/master/Illustrations/inj_obj_to_coll.PNG)

## Others

![](https://raw.githubusercontent.com/Ruslan-Aliyev/Spring-Lesson/master/Illustrations/others.PNG)

## Autowire

![](https://raw.githubusercontent.com/Ruslan-Aliyev/Spring-Lesson/master/Illustrations/autowire.PNG)

## Scopes

![](https://raw.githubusercontent.com/Ruslan-Aliyev/Spring-Lesson/master/Illustrations/spring_scopes.png)

## Accessing Context in Beans

![](https://raw.githubusercontent.com/Ruslan-Aliyev/Spring-Lesson/master/Illustrations/app_context_aware.jpg)

## Bean Inheritance

![](https://raw.githubusercontent.com/Ruslan-Aliyev/Spring-Lesson/master/Illustrations/inheritance.jpg)

## LifeCycle

![](https://raw.githubusercontent.com/Ruslan-Aliyev/Spring-Lesson/master/Illustrations/lifecycle.png)

https://howtodoinjava.com/spring-core/spring-bean-life-cycle/

## Post Processors

![](https://raw.githubusercontent.com/Ruslan-Aliyev/Spring-Lesson/master/Illustrations/Post_Processors.jpg)

## Annotations

![](https://raw.githubusercontent.com/Ruslan-Aliyev/Spring-Lesson/master/Illustrations/Annotation_Required.png)

![](https://raw.githubusercontent.com/Ruslan-Aliyev/Spring-Lesson/master/Illustrations/Annotation_Autowired.png)

![](https://raw.githubusercontent.com/Ruslan-Aliyev/Spring-Lesson/master/Illustrations/Annotation_Other_JSR250.png)

![](https://raw.githubusercontent.com/Ruslan-Aliyev/Spring-Lesson/master/Illustrations/Annotation_Stereotypes.png)

## Message Source

![](https://raw.githubusercontent.com/Ruslan-Aliyev/Spring-Lesson/master/Illustrations/MessageSource.png)

## Events

![](https://raw.githubusercontent.com/Ruslan-Aliyev/Spring-Lesson/master/Illustrations/Event.png)

## Aspect Orientated Programming

![](https://raw.githubusercontent.com/Ruslan-Aliyev/Spring-Lesson/master/Illustrations/Aspect.png)

https://www.journaldev.com/2583/spring-aop-example-tutorial-aspect-advice-pointcut-joinpoint-annotations

## Data

![](https://raw.githubusercontent.com/Ruslan-Aliyev/Spring-Lesson/master/Illustrations/Data1.jpg)

![](https://raw.githubusercontent.com/Ruslan-Aliyev/Spring-Lesson/master/Illustrations/Data2.png)
