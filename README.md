# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://frontendmentor.io). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

- Recreated a strict Neo-brutalism design with pixel-perfect sharp shadows and borders.

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page.
- View the optimal layout depending on their device's screen size (fully responsive).

### Screenshot

![Solution Screenshot](c:\Users\matve\Downloads\343shots_so.png)

### Links

- Solution URL: [https://frontendmentor.io[Matvey]](https://www.frontendmentor.io/profile/matvejbezvodinskih642-create)
- Live Site URL: [Frontend Mentor | Blog preview card](https://jovermer-frontend.github.io/blog-preview-card-main/)

## My process

- REM units system based on the 62.5% font-size root scaling method.
- I mastered alignment behaviors within Flexbox and Grid layouts. For instance, I discovered how child elements are stretched by default in a column layout and how to successfully override this behavior using `align-self: flex-start` to keep badges and custom shapes tight and compact, exactly like the static design files required.

### Built with

- Semantic HTML5 markup
- CSS Custom Properties (Variables)
- Flexbox & CSS Grid
- Modern Responsive Design (Fluid Typography & Spacing using `clamp()`)
- Mobile-first workflow approach
- BEM (Block Element Modifier) methodology

### What I learned

During this project, I learned how to work efficiently with modern Variable Fonts (`Figtree`) in CSS using just a single file for all font weights instead of multiple static files.

I also focused heavily on creating a truly fluid responsive layout without using single `@media` queries. By leveraging the power of `clamp()`, both the card paddings and the typography scale smoothly down to mobile sizes like 375px:

```css
/* Example of fluid responsive typography without media queries */
.blog-card__title {
  font-weight: 800;
  font-size: clamp(2.14rem, 5vw, 2.4rem);
  color: var(--Gray-950-color__title);
}
```

Furthermore, I mastered interactive accessible states by utilizing `:hover` for desktop mice and `:focus-visible` for keyboard-only navigation users.

### Continued development

In my next projects, I want to dive deeper into web accessibility (a11y) standards, advanced layout micro-animations, and CSS subgrid features.

## Author

- Frontend Mentor - @[Matvey](https://www.frontendmentor.io/profile/matvejbezvodinskih642-create)
- GitHub - @[jovermer-frontend](https://github.com/jovermer-frontend)
