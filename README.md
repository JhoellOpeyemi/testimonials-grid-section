# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)

  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)

- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I learnt more about Grid using the grid-template-areas property

```css
.grid {
	display: grid;
	grid-template-columns: repeat(4, 1fr);
	grid-template-rows: repeat(2, 1fr);
	grid-template-areas:
		'first first second fifth'
		'third fourth fourth fifth';
}
```

### Useful resources

- [DesignCourse short youtube video on grid template areas](https://www.youtube.com/watch?v=qTGbWfEEnKI) - This helped me understand grid template areas

## Author

- Frontend Mentor - [@JhoellOpeyemi](https://www.frontendmentor.io/profile/JhoellOpeyemi)
- Twitter - [@iam_jhoell](https://twitter.com/iam_jhoell)
