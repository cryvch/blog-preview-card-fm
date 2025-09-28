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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Blog preview card screenshot]<img width="1920" height="927" alt="Screenshot 2025-09-27 at 23-41-28 Frontend Mentor Blog preview card" src="https://github.com/user-attachments/assets/c7bbe14a-39f1-4615-99a7-c7c50f751133" />

### Links

- Solution URL: [GitHub Repo](https://github.com/cryvch/blog-preview-card-fm)
- Live Site URL: [Vercel Deployment](https://blog-preview-card-deployment.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

This project helped me practice **structuring content with semantic HTML** and applying **modern CSS layout techniques** like Flexbox for alignment.  

One small win was understanding why my footer attribution was misaligned — it was treated as a flex child of the `<body>`. The fix was to use `flex-direction: column` so it naturally stacked beneath the card.

```css
body {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
```

### Continued development

- I want to focus more on:

- Responsive design patterns for different screen sizes

- CSS Grid for more complex layouts

- Improving accessibility with ARIA roles and better keyboard focus states

### Useful Resources

- MDN Web Docs - Flexbox

- Frontend Mentor Community

### Author

GitHub - [cryvch](https://github.com/cryvch)

Frontend Mentor - [@cryvch](https://www.frontendmentor.io/profile/cryvch)

YouTube - [cryvch](https://www.youtube.com/@cryvch)
