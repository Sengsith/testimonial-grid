# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./screenshot.png)
![](./screenshot2.png)

### Links

- Solution URL: [GitHub](https://github.com/Sengsith/testimonial-grid)
- Live Site URL: [Netlify](https://famous-croquembouche-199ab5.netlify.app/)

## My process

The key focus of my completion of this challenge was attempting to implement a simple grid. I learned a lot with how and why I should keep a general and simple grid and the differences between an implicit and explicit grid. My workflow was done in order from writing custom properties, writing HTML, creating the grid, and then finishing up with styling the testimonials themselves.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I can't help but overthink the solution, but the grid turned out to be simpler than I thought. The initial process should be to try to keep it implicit and not to make the grid extremely strict with how many rows or columns it has.

```css
.testimonial-grid {
  display: grid;
  gap: 1.5rem;
  grid-auto-columns: 1fr;
  grid-template-areas:
  'one'
  'two'
  'three'
  'four'
  'five';
  ...
}
```

### Continued development

I learned a lot about grid but I would like to complete another project to see if I can figure it out in another design. The main part of grid I learned was using grid-template-areas and keeping it implicit.

## Author

- Frontend Mentor - [@Sengsith](https://www.frontendmentor.io/profile/sengsith)

## Acknowledgments

I tried to figure out the grid solution for myself but ended up learning a lot more by following some of the steps along by watching [Kevin Powell's video on Grid](https://youtu.be/rg7Fvvl3taU). It's great insight on how and why you should keep your CSS as general as possible to allow a simple grid implementation and reusability aroudn the project.
