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

--

--

---

## Tools

<img src="/images/java-logo.png" width="125" height="125" style="  border: 10px solid rgba(255,255,255,.5)">
<img src="/images/maven-logo.png" width="255" height="125" style="  border: 10px solid rgba(255,255,255,.5)">
<img src="/images/spring-logo.png" width="175" height="125" style="  border: 10px solid rgba(255,255,255,.5)">

---

## More markdown (code)

```
version: '2'
services:
  slides:
    image: msoedov/hacker-slides

    ports:
      - 8080:8080
    volumes:
      - ./slides:/app/slides
    restart: always

    environment:
     - USER=bob
     - PASSWORD=pa55

```

--

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
