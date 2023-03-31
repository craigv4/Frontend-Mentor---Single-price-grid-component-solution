# Frontend Mentor - Single price grid component solution

This is a solution to the
[Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc).
Frontend Mentor challenges help you improve your coding skills by building
realistic projects.

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

- View the optimal layout for the component depending on their device's screen
  size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](https://github.com/craigv4/Frontend-Mentor---Single-price-grid-component-solution/blob/main/Desktop%20Design.jpg)

![](https://github.com/craigv4/Frontend-Mentor---Single-price-grid-component-solution/blob/main/Mobile%20Design.jpg)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

```html
<p><span>&dollar;29</span> &#47; per month</p>
<p>Full access for less than &dollar;1 &#47; day</p>
```

```css
@media only screen and (min-width: 425px) {
  section {
    grid-template-columns: 1fr 1fr;
  }
  .container1 {
    grid-column-start: 1;
    grid-column-end: 4;
  }
  .container2,
  .container3 {
    grid-template-columns: 1fr 1fr;
  }
}
```

## Author

- Website - [Github](https://github.com/craigv4)
