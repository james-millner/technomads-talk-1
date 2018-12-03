# Introduction to Spring
### Building a Web App in 60 seconds, or there abouts.
#### By James Millner
#### https://james-millner.github.io/

<!-- .slide: data-transition="zoom" -->

---

## Who am I?

James Millner

(Not the footballer) 

--

<img src="/images/james-milner.jpg" width="550" height="300" style="  border: 10px solid rgba(255,255,255,.5)">

--

## Software Engineer

--

## Java Primarily

With abit of Go on the side.

---

##  What am I going to talk about?

---

## Web Development 

--

## Building applications fast using the latest frameworks and tooling.

--

## Scalable standalone applications

--

## Flexible and easy to work with

--

## Live Example

<img src="/images/demo-gods.jpg" width="400" height="375" style="  border: 10px solid rgba(255,255,255,.5)">

---

## What are Web Applications?

At its simplest: 

A web app is a client-server system whereby the client is an interface within a web browser that communicates information over the web via a server.

The server is collection of assets that are managed and distributed over the web via HTTP requests.

--

## Headless?

Web applications can also be headless and can be interacted with via REST interfaces, Sockets.

We all love API's!

<img src="/images/rest-api.jpeg" width="350" height="200" style="  border: 10px solid rgba(255,255,255,.5)">

--

## A not so long time ago

--

## Previously

This was as simple as:

- Views = HTML & CSS
- Business Logic - Done with typically PHP, ASP, JSP

All manually managed.

--

<img src="/images/what-is-mvc.jpeg" width="425" height="300" style="  border: 10px solid rgba(255,255,255,.5)">

---

## The Future! 

<img src="/images/future.png" width="600" height="400" style="  border: 10px solid rgba(255,255,255,.5)">

--

## An Introduction to Web MVC
What is it?

--

## A Modern Archtectural Pattern
The MVC pattern is the process of separating business logic, input logic and view logic in the form of Models, Views and Controllers.

- Models are structures used by the application for data.
- Views are responsible for rendering the model data.
- Controllers are responsible for processing user requests and building an appropriate model and passes it to the view for rendering.

--

## Spring Framework

Spring Framework is a Web MVC framework for Java.

Spring Boot is designed to get you up and running as quickly as possible, with minimal upfront configuration of Spring.

--

## Docker

A tool for developers that allows us to easily pack, ship, and run any application.

Docker builds apps as a lightweight, portable, self-sufficient containers, which can run virtually anywhere. Similar to Virtual machines but not quite.

--

## What we'll cover

- Setting up a web application project
- Explore creating a headless web service
- Create some core HTML for the web app to serve up
- Adding models and data into the HTML
- Creating a docker image of the application for preparing to deploy

---

## What you'll need:

--
## Tools

<img src="/images/java-logo.png" width="125" height="125" style="  border: 10px solid rgba(255,255,255,.5)">
<img src="/images/maven-logo.png" width="255" height="125" style="  border: 10px solid rgba(255,255,255,.5)">
<img src="/images/spring-logo.png" width="175" height="125" style="  border: 10px solid rgba(255,255,255,.5)">

--

## Validate tools - Java

java -version

```
Jamess-MBP:~ jamesmillner$ java -version
java version "1.8.0_162"
Java(TM) SE Runtime Environment (build 1.8.0_162-b12)
Java HotSpot(TM) 64-Bit Server VM (build 25.162-b12, mixed mode)
```
--

## Validate tools - Maven

A build automation tool.

mvn -v
```
Jamess-MBP:~ jamesmillner$ mvn -v
Apache Maven 3.5.2 (138edd61fd100ec658bfa2d307c43b76940a5d7d; 2017-10-18T08:58:13+01:00)
Maven home: /usr/local/Cellar/maven/3.5.2/libexec
Java version: 1.8.0_162, vendor: Oracle Corporation
Java home: /Library/Java/JavaVirtualMachines/jdk1.8.0_162.jdk/Contents/Home/jre
Default locale: en_GB, platform encoding: UTF-8
OS name: "mac os x", version: "10.14.1", arch: "x86_64", family: "mac"
```

--

## Spring

https://start.spring.io/

--

## Docker (Optional)

docker version
```
Jamess-MacBook-Pro:~ jamesmillner$ docker version
Client: Docker Engine - Community
 Version:           18.09.0
 API version:       1.39
 Go version:        go1.10.4
 Git commit:        4d60db4
 Built:             Wed Nov  7 00:47:43 2018
 OS/Arch:           darwin/amd64
 Experimental:      false

Server: Docker Engine - Community
 Engine:
  Version:          18.09.0
  API version:      1.39 (minimum version 1.12)
  Go version:       go1.10.4
  Git commit:       4d60db4
  Built:            Wed Nov  7 00:55:00 2018
  OS/Arch:          linux/amd64
  Experimental:     false
```

--

## Let's get started!

---

## Learn more

- [MVC - By Martin Fowler](https://martinfowler.com/eaaDev/uiArchs.html#ModelViewController)
- [Spring Framework](https://spring.io/)
- [Spring Boot Guide](https://spring.io/guides/gs/spring-boot/)
- [Kotlin](https://kotlinlang.org/docs/reference/)
- [Follow me on Github @ james-millner](https://github.com/james-millner)
