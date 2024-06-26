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

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- CUBE CSS
- BEM

**Note: These are just examples. Delete this note and replace the list above with your own choices**

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
