# Introduction to Spring
### Building a Web App in 60 seconds, or there abouts.
#### By James Millner

<!-- .slide: data-transition="zoom" -->

---

## Who am I?

James Millner - Java Developer

(Not the footballer) 


---

##  Building Web Applications

That are: 

---

## Fast

--

## Scalable

--

## Flexible and easy to work with

---

## More markdown (tables)

****

|h1|h2|h3|
|-|-|-|
|a|b|c|

****

--

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
