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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![Desktop View](./design/desktop-view-solution.png)

### Links

- Solution URL: [Github](https://github.com/sapgit97/fm-preview-card)
- Live Site URL: [Github Page](https://github.com/sapgit97/fm-preview-card)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Preventing flex from shrinking content at will
```css
.non-shrinking-flex-item{
  flex-shrink: 0;
}
```

Background image with color overlay
```css
.background-image-with-color-overlay {
  background: linear-gradient(hsla(277, 64%, 61%, 0.589), hsla(277, 64%, 61%, 0.589)), url(image-url);
}
```

### Continued development

Overlaying background image with some color, using grid, print media query are some of the new things I got to learn while working on this project. I would definitely like to explore it more. And loved the color palette, would definitely like to come up with such unique color palettes in future by myself.

### Useful resources

- [Web.dev Css Course](https://web.dev/learn/css/) - Awesome resource to recap css fundamentals
- [Kevin Powell's YouTube Channel](https://www.youtube.com/channel/UCJZv4d5rbIKd4QHMPkcABCw) - Great, concise explanations.

## Author

- Frontend Mentor - [@sapgit97](https://www.frontendmentor.io/profile/sapgit97)
- Twitter - [@poisoncoreSM](https://www.twitter.com/poisoncoreSM)
