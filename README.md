# Bootcamp Challege-2: Professinal Portfolio - Growing Up

## Table of contents

- [Overview](#overview)
  - [Purpose](#purpose)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Purpose
A website designed to show my work when applying for a job. 

### The challenge

Users should be able to:

- reach the corresponding title by clicking on the navigation.
- see the developer's name, photos, and links to sections about developer, works, and how to contact developer.
- click the images of applications to transfer into deployed application.
- resize the page or view the site on various screens and devices.

### Screenshot

![](./assets/images/Professional%20Portfolio%20-%20Growing%20Up%20-%20yanglongwang.github.io.png)

### Links

- Solution URL: [https://github.com/YangLongWang/Bootcamp-Challege-2-Professional-Portfolio](https://github.com/YangLongWang/Bootcamp-Challege-2-Professional-Portfolio)
- Live Site URL: [https://yanglongwang.github.io/Professional-Portfolio/](https://yanglongwang.github.io/Professional-Portfolio/)

## My process

### Build with

- Semantic HTML
- CSS

### What I learned

- using media queries to change the properties and the website's width to reach users can check the website on various screens and devices.
- Make the heading part stick to the top of the page.
- Practice using flex boxes.

To see how I add code snippets, see below:

```css
@media screen and (max-width: 980px) {
    header {
        padding: 25px;
    }

    p {
        text-align: center;
    }

    .text p {
        text-align: left;
    }

    .applications {
        padding: 0 40px;
    }

    footer {
        padding: 10px;
    }
}

header {
    padding: 30px;
    background-color: black;
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    position: -webkit-sticky;
    position: sticky;
    top: 0;
    z-index: 10;
}
```

## Author

- Github - [Longyang Wang](https://github.com/YangLongWang)


