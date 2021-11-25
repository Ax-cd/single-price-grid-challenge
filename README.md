# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](images/single-price-grid-screenshot.png)


### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/single-price-grid-using-css-grid-nDCJ5WYrH)
- Live Site URL: [GitHub Page](https://github.com/Ax-cd/single-price-grid-challenge)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow
- CSS Grid


### What I learned

First time I used CSS Grid in a project, so I'm happy to have figure it out. It all clicked once I remembered the span value.

```css
@media (min-width: 80em) {
    main {
        max-width: 40%;
        display: grid;
    }
}

@media (min-width: 40em) {
    .introduction {
        grid-column: span 2;
    }
}
```

### Continued development

- Projects using Grid to be comfortable using the differents properties and values it offers.


### Useful resources

- [MDN Web Docs: grid-template](https://developer.mozilla.org/fr/docs/Web/CSS/grid-template) - The CSS Demo part and the syntaxe part were a helpful reminder on how to define the grid the way I needed.


## Author

- Website - [Ax-cd](https://axcoding.blogspot.com/)
- Frontend Mentor - [@Ax-cd](https://www.frontendmentor.io/profile/Ax-cd)
- Instagram - [@ax.coding](https://www.instagram.com/ax.coding/)
