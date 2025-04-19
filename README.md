# Frontend Mentor - Product preview card component

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects with professional designs.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Desktop version](./design/desktop-preview.jpg)

### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/product-preview-card-component-LecM-nTFV2)
- Live Site URL: [View Live](https://mobina-dev-2001.github.io/Product-preview-card-component/)

## My process

### Built with

- Semantic HTML5
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Responsive images using `srcset` and `sizes`

### What I learned

This project helped reinforce my understanding of writing semantic HTML and building accessible components. I practiced using `srcset` for responsive images and CSS techniques like `clamp()` for responsive spacing and typography.

Here’s a snippet I was happy with:

```css
.product-desc-container {
  display: flex;
  flex-direction: column;
  gap: 1.3rem;
  padding: clamp(1.5rem, 4vw, 2rem);
}
```
