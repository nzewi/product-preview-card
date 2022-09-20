# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./project-screenshot.jpg)


### Links

- Solution URL: [Add solution URL here](https://github.com/nzewi/product-preview-card)
- Live Site URL: [Add live site URL here](https://nzewi.github.io/product-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- BEM


### What I learned

- I learnt how to change the image rendered based on different screen sizes using background-image property
  ```html
  <div class="card__img"></div>
  ```
  ```css
  .card__img {
  background-image: url(./images/image-product-mobile.jpg);
  background-size: cover;
  background-repeat: no-repeat;
  }
  @media (min-width: 90em) {
  .card__img {
    background-image: url(./images/image-product-desktop.jpg);
  }
  } 
  ```
- I learnt how to build mobile-first designs


### Continued development

- Using flexbox and grid to build responsive components
- Using media queries to build responsive components

## Author

- Frontend Mentor - [@nzewi](https://www.frontendmentor.io/profile/nzewi)
- Twitter - [@nelson_nzewi](https://www.twitter.com/nelson_nzewi)
