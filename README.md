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
- See hover and focus states for interactive elements

### Screenshot

![Imgur](https://i.imgur.com/JWKA0nW.jpeg)

### Links

- Solution URL: [https://your-solution-url.com](https://your-solution-url.com)
- Live Site URL: [https://ko-statspreviewcardcomponent.vercel.app/](https://ko-statspreviewcardcomponent.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I followed a mobile-first workflow for the first time: I built the mobile layout first and then used a media query to switch the image and text order for desktop. I also learned how to apply a color overlay on top of an image using `background-color` with `mix-blend-mode`.

```css
.image {
  position: relative;
}

.image::after {
  content: "";
  position: absolute;
  inset: 0;
  background-color: hsl(277, 64%, 61%);
  mix-blend-mode: multiply;
}
```

### Continued development

I want to keep practicing the mobile-first approach on future projects, since it forced me to think about the essential content first before adding complexity for larger screens.

### Useful resources

- [MDN - mix-blend-mode](https://developer.mozilla.org/en-US/docs/Web/CSS/mix-blend-mode) - Helped me understand how to blend a color overlay with an image without needing an extra image asset.

## Author

- Frontend Mentor - [@KevinOrt218](https://www.frontendmentor.io/profile/KevinOrt218)
- Instagram - [@kevin_v.o18](https://www.instagram.com/kevin_v.o18)
