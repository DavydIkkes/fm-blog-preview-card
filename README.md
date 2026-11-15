# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

- See hover and focus states for all interactive elements on the page

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS variables
- font-face properties
- BEM

### What I learned

Used BEM for apply styles to the elements into HTML, also moved into CSS file from up to down in a convinient way:

```html
<p class="card__tag">Learning</p>
<p class="card__date">Published 21 Dec 2023</p>
<h2 class="card__title">HTML & CSS foundations</h2>
<p class="card__description">
    These languages are the backbone of every website, defining
    structure, content, and presentation.
</p>
```

Used font-face properties for custom fonts into CSS:
```css
@font-face {
    font-family: "Figtree Extra Bold";
    src: url("assets/fonts/static/Figtree-ExtraBold.ttf");
}
```

Splitted default variables into sections:
```css
:root {
    /* Colors */
    --yellow: #F4D04E;
    --gray-950: #111111;
    --gray-500: #6B6B6B;
    --white: #FFFFFF;

    /* Fonts */
    --figtree-bold: "Figtree Extra Bold", sans-serif;
    --figtree-medium: "Figtree Medium", sans-serif;
}
```

Used pseudo-class `:hover`:
```css
.card__title:hover {
    color: var(--yellow);
}
```


### Continued development

In future I will improve BEM usage into HTML/CSS and try to use some JS.

### Useful resources

- [BEM Quickstart](https://bem.info/ru/methodology/quick-start/) - This help me to understand how to use BEM while naming classes during the HTML layout.

## Author

- Frontend Mentor - [@DavydIkkes](https://www.frontendmentor.io/profile/DavydIkkes)
