# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/solutions/responsive-testimonial-cards-using-css-grid-IBNjU-oJHC). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Desktop Screenshot](./screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/responsive-testimonial-cards-using-css-grid-IBNjU-oJHC)
- Live Site URL: [Add live site URL here](https://rishabhsikka3.github.io/testimonials-grid/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

While working on this project, I learned how to:

- Use `:nth-child()` selectors more effectively to target specific testimonial cards by their index:

  ```css
  .testimonial:nth-child(1),
  .testimonial:nth-child(2),
  .testimonial:nth-child(5) {
    color: var(--white);
  }

  .testimonial:nth-child(n + 3):nth-child(-n + 4) .profile-details .name {
    color: var(--grey-500);
  }
  ```

- Apply background images with spacing using `background-position` like:

  ```css
  background-position: top right 2rem;
  ```

### Continued development

I want to continue improving my CSS Grid skills, especially with responsive layouts using `auto-fit` and `auto-fill`, and refine my knowledge of specificity handling in nested selectors.

### Useful resources

- [MDN Web Docs - :nth-child()](https://developer.mozilla.org/en-US/docs/Web/CSS/:nth-child) - Excellent reference for understanding complex selectors.
- [CSS Tricks - A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - Helped me understand the difference between `auto-fit` and `auto-fill`.

## Author

- Name - Rishabh Sikka
- Frontend Mentor - [@RishabhSikka3](https://www.frontendmentor.io/profile/RishabhSikka3)

## Acknowledgments

Big thanks to the Frontend Mentor community.
