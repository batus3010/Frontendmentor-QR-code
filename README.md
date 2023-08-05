# Frontendmentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H)

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![](./design/screenshot.png)

### Links
- Solution URL: https://github.com/batus3010/Frontendmentor-QR-code
- Live site URL: https://batus3010.github.io/Frontendmentor-QR-code/

## My process 

### Built with 
- Semantic HTML5 markup 
- CSS custom properties 
- Flexbox

### What I learned 

- Put elements inside a container, set the height of it to 100vh and use CSS flexbox to position it at the center of screen 
```css
    .container{
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
    }
```
- Using media queries to make the site more responsive with different screen size
```css
    @media screen and (max-width: 768px) {
      .card {
        /*customized style for screen equal to and below 768px*/
      }
    }
    @media screen and (min-width: 769px) {
      .card {
        /*style for screen size above 769px*/
      }
    }
```

### Continue development

Currently I'm learning CSS Grid and playing around with Bootstrap framework. CSS Flexbox and Grid are amazing tools and helped me a lot with positioning items.
