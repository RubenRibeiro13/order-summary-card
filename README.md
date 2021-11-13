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

![](screenshots/screenshot-desktop.png)
![](screenshots/screenshot-mobile.png)

### Links

- Solution URL: [https://github.com/RubenRibeiro13/order-summary-card](https://github.com/RubenRibeiro13/order-summary-card)
- Live Site URL: [https://rubenribeiro13.github.io/order-summary-card](https://rubenribeiro13.github.io/order-summary-card)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

While working through this project, I learned the basics of media queries and flexbox, how to set background images and how to add shadow effects.

```css

@media screen and (max-width: 600px), (min-width: 1200px) {
}

.container {
  display: flex;
  flex-flow: row nowrap;
  justify-content: space-evenly;
  align-items: center;
}

body {
  background-image: url("images/pattern-background-desktop.png");
  background-repeat: no-repeat;
  background-size: 100% auto;
}

.white-bg {
  box-shadow: 0 30px 30px #dedbf8;
}

```

### Continued development

In future projects, I want to continue focusing on media queries and flexbox. I also want to start learning the basics of CSS Grid.

### Useful resources

- [CSS-Tricks](https://css-tricks.com) - This resource helped me understand what a flexbox is and how/when to use it.
- [W3Schools Online Web Tutorials](https://www.w3schools.com) - This resource gave me an idea of which breakpoints to use in media queries.
- [MDN Web Docs](https://developer.mozilla.org) - This is my go-to resource when I need to use a property for the first time, such as background-image or box-shadow.

## Author

- Website - [Ruben Ribeiro](https://rubenribeiro13.github.io/my-site)
- Frontend Mentor - [@RubenRibeiro13](https://www.frontendmentor.io/profile/RubenRibeiro13)

## Acknowledgments

I'd like to thank one of my best friends, João Gonzalez, for introducing me to the flexbox module.
