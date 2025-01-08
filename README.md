# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./screenshot/Screenshot%20Frontend%20Mentor%20QR%20code%20component.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

Redoing the challenge once again for practice.

See my previous code by clicking [here](https://github.com/cdGuilherme/qr-code-challenge).

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Responsive design

### What I learned

My objective with this challenge was getting as close to the design as possible while using semantic elements, ensuring responsive layout and best practices such as BEM naming convention.

```html
<!-- Semantic element -->
<main>
  <div class="container">
    <!-- BEM naming convention -->
    <div class="container__img"></div>
    <div class="container__text"></div>
  </div>
</main>
```

```css
:root {
  --white: hsl(0, 0%, 100%); /* CSS custom property */
  /* ... */
}
```

```css
.container {
  max-width: 18rem; /* Responsive layout */
  /* ... */
  margin: 1rem; /* Relative units */
}
```

### Continued development

Looking for feedback about what I might have missed or could've done better.

### Useful resources

Some resources I've used during this challenge:

- [HTML Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp)
- [BEM naming convention](https://en.bem.info/methodology/naming-convention/)
- [CSS @import Rule](https://www.w3schools.com/cssref/atrule_import.php)
- [CSS Variables - The var() Function](https://www.w3schools.com/css/css3_variables.asp)
- [CSS Units](https://www.w3schools.com/cssref/css_units.php)

## Author

- Frontend Mentor - [@cdGuilherme](https://www.frontendmentor.io/profile/cdGuilherme)
