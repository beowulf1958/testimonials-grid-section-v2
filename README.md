# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Screenshot](/images/Screenshot%202024-06-26%20testimonial%20page.png)

### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/responsive-page-with-cube-and-bem-vanilla-html-css-BJFMT6lczk)
- Live Site URL: [Add live site URL here](https://testimonial-v2.netlify.app/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- CUBE CSS
- BEM

### What I learned

Great review of grid. I did this twice: once using explicit line numbers to place items in the grid, and then using grid-template-areas. I went with the grid-template areas because it is easier to see where everything goes.

```css
main {
  width: 80%;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-template-rows: 1fr 1fr;
  gap: 20px;
  grid-template-areas:
    "daniel daniel jonathan kira"
    "jeanette patrick patrick kira";
}
```

### Continued development

This was done without Sass; I will be going back to Sass and learning about mixins.

### Useful resources

- [Resource 1](https://css-tricks.com/snippets/css/complete-guide-grid/) - This helped me reference the different grid properties. I really liked this pattern and will use it going forward.
- [Resource 2](https://www.freecodecamp.org/news/complete-guide-to-css-grid/) - This is an amazing article which helped me look up properties quickly. I'd recommend it to anyone still learning this concept.

## Author

- Frontend Mentor - [@beowulf1958](https://www.frontendmentor.io/profile/beowulf1958)
