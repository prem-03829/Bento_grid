# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the interface depending on their device's screen size

### Screenshot

<div style="display: flex; flex-direction: column; justify-content: center; align-items: center; gap: 1rem;">
<img src="assets/images/screenshots/desktop-screenshot.png">
<img src="assets/images/screenshots/mobile-screenshot.png" width="300">
</div>

### Links

- Solution URL: [GitHub repo](https://github.com/prem-03829/Bento_grid)
- Live Site URL: [Vercel link](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5  
- CSS custom properties (design tokens)  
- CSS Grid  
- Flexbox  
- Desktop-first workflow  
- Mobile-responsive layout
- Responsive media queries  
- Custom design system for typography & spacing  
- Accessibility-friendly HTML structure
- Reusable CSS utility patterns


### What I learned
This challenge pushed me to structure CSS more professionally:

- This project taught me how powerful a structured :root {} system can be.
  This was my first time writing CSS this efficiently, using proper design tokens for font sizes, spacing, colors, line-height, and letter-spacing. It completely changed how I approach styling—everything became more consistent, scalable, and easier to maintain.
```css
:root {
  --fs-xl: 1.6rem;
  --ls-sm: -0.1em;
  --lh-md: 1.5rem;
  --purple-500: hsl(256, 67%, 59%);
}
```

- Building a complex responsive grid using grid-template-areas
```css
grid-template-areas:
  "a b b c"
  "d e f c"
  "d g h h";
```

- Using max-height to prevent overflow
```css
.c img {
  max-height: 14rem;
}
```

- Letter-spacing in em instead of rem

### Continued development

- Refine my design-token system so it's reusable in future projects
- Improve responsive typography using clamp() and fluid units
- Practice more advanced CSS Grid patterns
- Strengthen accessibility (semantic HTML, alt text, heading hierarchy)
- Write cleaner, more maintainable CSS with less duplication


### Useful resources

- [Bento grid youtube tutorial](https://youtu.be/v0o1kV-qfVI?si=52lfs_CYjwTBG8R-) - This video helped me understand how to build a bento-style grid layout

## Author

- LinkedIn - [Prem Paramanick](https://www.linkedin.com/in/prem-paramanick-a46205338)
- Frontend Mentor - [@prem-03829](https://www.frontendmentor.io/profile/prem-03829)
- GitHub - [@prem-03829](https://github.com/prem-03829)

## Acknowledgments

This project genuinely made me feel like I accomplished something, it was my first time working on a challenge this demanding, and the final result really boosted my confidence. It’s easily my best frontend project yet, and I spent around 6 hours refining every detail until it matched the original pixel-for-pixel. Huge thanks to Frontend Mentor for providing all the assets, which let me focus entirely on the build instead of hunting for resources. I’m still learning and improving, but this project showed me that I’m on the right path, and I’m proud of the progress I made here.