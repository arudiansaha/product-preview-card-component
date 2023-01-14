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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

#### Desktop Version

- [Desktop version](./sceenshots/screenshot-desktop.png)

#### Mobile Version

- [Mobile version](./sceenshots/screenshot-mobile.png)

### Links

- Solution URL: [https://github.com/arudiansaha/product-preview-card-component](https://github.com/arudiansaha/product-preview-card-component)
- Live Site URL: [https://arudiansaha.github.io/product-preview-card-component](https://arudiansaha.github.io/product-preview-card-component)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

What I learned so far is best practice for naming class on css and use semantic HTML5 to make my code easy to understand, and looks clean. Oh ya! I need feedback for my code to gain more knowledge from all of you 😊.

Here some code of mine:

```html
<header class="description__header">
  <span class="description__categories description__categories--blue2">PERFUME</span>
  <h1 class="description__title description__title--blue1">Gabrielle Essence Eau De Parfum </h1>
</header>
```
```css
.description__header {
    padding-inline: 2rem;
}

.description__categories {
    font-family: 'Montserrat';
    font-size: var(--font-size-text);
    letter-spacing: 0.5em;
}

.description__categories--blue2 {
    color: var(--neutral-color-blue2);
}

.description__title {
    font-family: 'Fraunces';
    font-size: var(--font-size-title);
    line-height: 1;
}

.description__title--blue1 {
    color: var(--neutral-color-blue1);
}
```

### Continued development

~~Some issues I founded, when the higth are low the card just show half of the content. Hope to fix this issues ASAP.~~

### Useful resources

- [What On Earth Is Semantic Markup? (And Why Should You Learn To Write It)](https://html.com/semantic-markup/) - This helped me for avoid the div element as posible.
- [A Complete Guide to Custom Properties](https://css-tricks.com/a-complete-guide-to-custom-properties/) - This is an amazing article which helped me to understand with custom properties on css.

## Author

- Website - [My personal blog](https://rizkyardiansyah.tech)
- Frontend Mentor - [@arudiansaha](https://www.frontendmentor.io/profile/arudiansaha)
- Twitter - [@arudiansaha](https://www.twitter.com/arudiansaha)
- Linkedin - [Rizky Ardiansyah](https://www.linkedin.com/in/ky-ardiansyah/)

## Acknowledgments

### Big Thanks

- [@correlucas](https://www.frontendmentor.io/profile/correlucas) - Thanks to @correlucas for helping me to fix overflow issues.
- [A Complete Guide to Custom Properties](https://css-tricks.com/a-complete-guide-to-custom-properties/)
- [What On Earth Is Semantic Markup? (And Why Should You Learn To Write It)](https://html.com/semantic-markup/)
- [W3Schools CSS Reference](https://www.w3schools.com/cssref/default.asp)
- [W3Schools HTML Element Reference](https://www.w3schools.com/tags/default.asp)
- [Tailwind CSS Docs](https://tailwindcss.com/docs/)