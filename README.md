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
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./images/screenshot.jpg)
![](./images/screenshot-mobile.jpg)

### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/product-preview-card-using-css-grid-and-mobilefirst-workflow-4aoWiSotDC)
- Live Site URL: [Product Preview Card](https://cgrkzlkn.github.io/product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 Markup
- CSS Grid
- Mobile-First Workflow

### What I learned

Changing the image depending to screen size:

```html
<picture class="img-container">
  <source
    srcset="./images/image-product-desktop.jpg"
    media="(min-width: 1440px)"
  />
  <img src="./images/image-product-mobile.jpg" alt="Perfume" />
</picture>
```

To make a card with equal width columns grid layout:

```css
.card {
  display: grid;
  grid-auto-flow: column;
  grid-auto-columns: minmax(0, 1fr);
  width: 600px;
}
```

### Useful resources

- [Stack Overflow](https://stackoverflow.com/questions/47601564/equal-width-columns-in-css-grid) - This answer helped me to make a card with equal width columns grid layout.

## Author

- Website - [Cagri Kizilkan](https://cagrikizilkan.com)
- Frontend Mentor - [@cgrkzlkn](https://www.frontendmentor.io/profile/cgrkzlkn)
- Twitter - [@cgrkzlkn](https://www.twitter.com/cgrkzlkn)
