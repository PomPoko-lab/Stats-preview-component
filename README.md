# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](images/completed.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Challenge DEMO](https://pompoko-lab.github.io/Stats-preview-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

- The toughest part of this challenge was again, overlaying a color over an image and sizing all of the image related contents. After this challenge, I am more confident on performing a task like this.

```css
div {
  background-image: linear-gradient(
      hsla(273, 100%, 26%, 0.6),
      hsla(273, 100%, 26%, 0.6)
    ), url("images/image-header-desktop.jpg");
  background-size: cover;
  border-top-right-radius: 0.5em;
  border-bottom-right-radius: 0.5em;
}
```

- More CSS grid but this time, with responsive design.
