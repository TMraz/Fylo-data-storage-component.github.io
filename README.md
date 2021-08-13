# Frontend Mentor - Fylo data storage component solution

This is a solution to the ![Fylo data storage component challenge on Frontend Mentor](./design/desktop-preview.jpg). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

[Desktop version](./design/desktop-design.jpg)
[Mobile version](./design/mobile-design.jpg)

### Links

- [Solution URL](https://github.com/TMraz/Fylo-data-storage-component.github.io)

- [Live Site URL](https://tmraz.github.io/Fylo-data-storage-component.github.io/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Styled Components](./css/main.css) - For Desktop style
- [Styled Components](./css/mobile.css) - For Mobile style

### What I learned

Snippets, see below:

Color gradient

```css
    --color-gradient: linear-gradient(0.25turn, hsl(6, 100%, 80%), hsl(335, 100%, 65%));

```

Arrow

```html
<!-- === triagle === -->
<div class="arrow-left"></div>
```

```css
/* === triangle === */  
.arrow-left {
    width: 0; 
    height: 0; 
    border-top: 20px solid transparent;
    border-bottom: 20px solid transparent; 

    border-right: 20px solid var(--color-font); 

    margin-top: 3rem;
}

```

### Useful resources

- [Color gradient](https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/linear-gradient())
- [Arrow draw in CSS](https://css-tricks.com/snippets/css/css-triangle/) - This is an amazing article which helped me draw the arrow in CSS.
