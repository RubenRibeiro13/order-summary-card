# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
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

### Screenshots

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

While working through this project, I learned the basics of HTML sectioning elements, flexbox and media queries, what a mobile-first responsive design is, and how to set background images and add shadow effects.

```html

<footer>
  <div class="main-div">
    <div class="attribution">
      Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>.
      Coded by <a href="https://rubenribeiro13.github.io/my-site/">Ruben Ribeiro</a>.
    </div>
  </div>
</footer>

```

```css

.container {
  background-color: hsl(225, 100%, 98%);

  box-sizing: border-box;
  padding: 5%;
  width: 85%;
  max-width: 350px;
  margin: 30px auto;

  border-radius: 10px;

  display: flex;
  flex-flow: row nowrap;
  justify-content: space-between;
  align-items: center;
}

.white-bg {
  background-color: white;

  width: 100%;
  padding: 11% 0;

  border-radius: 0 0 20px 20px;
  box-shadow: 0 40px 15px rgb(220, 220, 250);
}

body {
  margin: 0;

  background-color: hsl(225, 100%, 94%);
  background-image: url("images/pattern-background-mobile.png");
  background-repeat: no-repeat;
  background-size: 100% auto;

  text-align: center;
  font-family: 'Red Hat Display', sans-serif;
}

@media screen and (min-width: 900px) {
  body {
    background-image: url("images/pattern-background-desktop.png");
  }
}

```

### Continued development

In future projects, I want to continue focusing on HTML sectioning elements, flexbox and media queries. I also want to start learning the basics of CSS Grid.

### Useful resources

- [CSS-Tricks](https://css-tricks.com) - This resource helped me understand more about HTML sectioning elements and flexbox.
- [W3Schools](https://www.w3schools.com) - This resource gave me an idea of which breakpoints to use in media queries.
- [MDN Web Docs](https://developer.mozilla.org) - This is my go-to resource when I need to use a property for the first time, such as background-image or box-shadow.
- [Stack Overflow](https://stackoverflow.com) - This resource is helpful when I'm not sure which property or properties should be used to accomplish a certain task.

## Author

- Website - [Ruben Ribeiro](https://rubenribeiro13.github.io/my-site)
- Frontend Mentor - [@RubenRibeiro13](https://www.frontendmentor.io/profile/RubenRibeiro13)

## Acknowledgments

I'd like to thank one of my best friends, João Gonzalez, for introducing me to the flexbox module.
