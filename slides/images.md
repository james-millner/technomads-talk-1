# Introduction to Spring
### Building a Web App in 60 seconds, or there abouts.
#### By James Millner

<!-- .slide: data-transition="zoom" -->

---

## Who am I?

James Millner - Java Developer

(Not the footballer) 


---

##  What am I going to talk about?

---

## Web Development

--

## Building applications, and focusing on the good stuff

--

## Scalable standalone applications

--

## Flexible and easy to work with

---

## What are Web Applications?

At its simplest, its a collection of assets that are managed and distributed over the web via HTTP requests.

It can be multilayered with view assets, business logic and data access.

---

## Previously

This was as simple as:

- Views = HTML & CSS
- Business Logic - Inlined PHP / JavaScript
- Data access - Inlined PHP / JavaScript

All manually managed.

---

## An Introduction to Web MVC
What is it?

--

## A Modern Archtectural Pattern
The MVC pattern is the process of separating business logic, input logic and view logic in the form of Models, Views and Controllers.

- Models are structures used by the application for data.
- Views are responsible for rendering the model data.
- Controllers are responsible for processing user requests and building an appropriate model and passes it to the view for rendering.

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

## Let's get started!

---

## Local images

![demoPicture](/images/demo.png)

Copy images into slides/images/ & include with MD:

```
![demoPicture](/images/demo.png)

```
or HTML:

```
<img src="/images/demo.png">

```


---

## Learn more

- [RevealJS Demo/Manual](http://lab.hakim.se/reveal-js)
- [RevealJS Project/README](https://github.com/hakimel/reveal.js)
- [GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown)
