# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

Here is a screenshot of the page on imgbb.com<br>
<a href="https://ibb.co/s6K4MQy"><img src="https://i.ibb.co/xf1bRGJ/Web-capture-13-12-2021-144243-1guywebdev-fem-order-summary-component-netlify-app.jpg" alt="Web-capture-13-12-2021-144243-1guywebdev-fem-order-summary-component-netlify-app" border="0"></a>)

### Links

- Solution URL: [My solution](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj/hub/order-summary-component-using-mostly-flex-display-and-media-queries-HFbXBJ6ci)
- Live Site URL: [The site live on Netlify](https://1guywebdev-fem-order-summary-component.netlify.app/)

## My process

### Built with

- CSS custom properties
- Flexbox
- @media queries

### What I learned

I've learned about placing and sizing the background image with 
```css
.element {
  background-size: ;
  width: 100%;
  height: 100%;
```
To see how you can add code snippets, see below:

```html
<div class="background-img"></div>
```
```css
.background-img {
  background-image: url(../images/pattern-background-desktop.svg);
  background-size: cover;
  background-repeat: no-repeat;
  background-size: 100vw 55vh;
  position: absolute;
  z-index: -1;
  width: 100vw;
  height: 100vh;
  top: 0;
}
```

If you want more help with media queries, I'd recommend checking out [coderjony's blog](https://coderjony.com/blogs/media-queries-in-css-min-width-and-max-width/) to learn more.

### Continued development

I am still learning about media queries, and would love to get absolutely perfect at it.

### Useful resources

- [w3schools media queries section](https://www.w3schools.com/cssref/css3_pr_mediaquery.asp) - This helped me media queries. W3schools is great place to start understanding HTML, CSS, and JavaScript.

## Author

- Website - [1guywebdev](https://1guywebdev.github.io/)
- Frontend Mentor - [@1guywebdev](https://www.frontendmentor.io/profile/1guywebdev)

## Acknowledgments

I had some great advice from [@skyv26](https://www.frontendmentor.io/profile/skyv26) who helped me with the background image sizing and placing.
