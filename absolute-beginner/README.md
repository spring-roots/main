# Absolute Beginner

Learning about Spring for the first time.

## Audience

You're on the hook to work on a "Spring Application" (whatever that means), and you want to understand the fundamentals.

## Objectives

- Be able to say you've written a Spring-based app.
- Know the difference between Dependency Injection and Inversion of Control.

## Set up

- If you have never set up a Spring Project with Gradle or Maven, you may find this walkthrough beneficial: 
  - Gradle: https://spring.io/guides/gs/gradle/ 
  - Maven: https://spring.io/guides/gs/maven/
  
## Do

Recommendation: Set up two separate Spring applications for each of the Spring Applications below in order to be able to better see the similarities and differences between them. 

1. Write a "Hello, World!" Spring application — http://projects.spring.io/spring-framework/#quick-start
    - note this tutorial illustrates DI only.
    - the whole time, your application is in control of the flow of events.
1. Take "Hello, World!" to the web with Spring Boot: https://spring.io/guides/gs/rest-service/
    - note this tutorial includes IoC.
        - The line `SpringApplication.run(Application.class, args);` starts the IoC container and runs until the app is stopped.
        - the code you write (namely the controller) plugs-into the container.  The IoC container _controls_ the routing of the request to your code.
1. Check out the Spring ecosystem: https://spring.io/projects and feel the ~~overwhelm~~ amazement from its sheer size.

## Quiz

<details> 
  <summary> What is a Spring Bean?  </summary>
   *No one really knows tbh* 
</details>
<details> 
  <summary> What is an Application Context?  </summary>
   *I wish there was an answer. This is an unknowable mystery, like rubix cubes or crosswords* 
</details>
<details> 
  <summary> What is dependency injection?  How does Spring implement DI?  </summary>
   *Really this quiz was a bad idea, I guess it's when you force the program to swallow the dependency by adding it to the constructor*
</details>
<details>
  <summary> What is inversion of control?  How does Spring implement IoC? </summary>
  *It's DI's much prettier - yet sometimes higher maintenance - younger sister*
</details>
