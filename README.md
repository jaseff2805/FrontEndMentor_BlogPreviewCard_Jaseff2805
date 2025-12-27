
# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- See hover and focus states for all interactive elements on the page

### Screenshot

### Screenshot

![Blog preview card final design](./screenshot.png)

### Links

- Solution URL: https://github.com/jaseff2805/FrontEndMentor_BlogPreviewCard_Jaseff2805
- Live Site URL: https://jaseff2805.github.io/FrontEndMentor_BlogPreviewCard_Jaseff2805/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Bootstrap 5](https://getbootstrap.com/)
- Locally hosted [Figtree](https://fonts.google.com/specimen/Figtree) font
- Git & GitHub for version control

### What I learned

This project helped me practice building a small card component that still pays attention to details like spacing, shadows and typography.

Some highlights:

- Loading a local variable font with `@font-face` and using it as the main typeface:

\`\`\`css
@font-face {
  font-family: "Figtree";
  src: url("fonts/Figtree-VariableFont_wght.ttf") format("truetype");
  font-weight: 300 900;
  font-style: normal;
  font-display: swap;
}
\`\`\`

- Creating the “offset shadow” border effect on the card:

\`\`\`css
.card.card-blog {
  border: 1px solid var(--clr-gray-950);
  box-shadow: 12px 12px 0 0 var(--clr-gray-950);
}
\`\`\`

- Fixing layout issues caused by default flex behaviour in Bootstrap:

\`\`\`css
.card-blog .card-body {
  display: flex;
  flex-direction: column;
  align-items: flex-start; /* avoid stretching children full width */
}
\`\`\`

### Continued development

In future projects I’d like to keep improving on:

- Recreating designs with pixel-perfect spacing and typography.
- Getting more comfortable overriding Bootstrap styles without fighting the framework.
- Building reusable card components that can be reused in grids or lists.

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/) – For HTML and CSS reference.
- [Bootstrap documentation](https://getbootstrap.com/docs/5.3/getting-started/introduction/) – To understand the utility classes I used and how to override them.
- [Frontend Mentor](https://www.frontendmentor.io/) – For the original challenge and design.

## Author

- Frontend Mentor - https://www.frontendmentor.io/profile/jaseff2805
- GitHub - https://github.com/jaseff2805