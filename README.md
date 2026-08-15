# Frontend Mentor - Social Links Profile Solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

---

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Useful Resources](#useful-resources)
- [Author](#author)

---

## Overview

### The Challenge

Users should be able to:

- See hover and focus states for all interactive link buttons on the page
- Experience a clean, centered dark-mode social card profile across mobile and desktop devices

### Links

- **Live Site URL**: [Live Demo](https://mo-boop-ux.github.io/Social-Links-Profile/)
- **GitHub Repository**: [Social-Links-Profile](https://github.com/Mo-boop-ux/Social-Links-Profile)

---

## My Process

### Built With

- **Semantic HTML5** markup
- **CSS Flexbox** - Vertical card alignment and centered page layout
- **Google Fonts** - [Inter](https://fonts.google.com/specimen/Inter)
- **Modern Dark Theme** - Sleek dark backgrounds with vibrant neon green accent colors
- **Interactive Micro-Interactions** - Smooth hover feedback on navigation links

### What I Learned

Creating this profile card allowed me to refine compact card layouts and hover state styling:

1. **Interactive Link Buttons**:
   Building clean list elements with smooth background transitions on hover:

```css
ul li a {
    text-decoration: none;
    color: #ffffff;
    font-weight: 700;
    font-size: 14px;
    background: #333333;
    display: block;
    width: 280px;
    text-align: center;
    padding: 12px 0;
    border-radius: 8px;
    transition: background-color 0.2s ease, color 0.2s ease;
}

ul li a:hover {
    background: #c5f82a;
    color: #141414;
}
```

2. **Avatar Styling**:
   Centered circular profile image with proper proportions:

```css
img {
    width: 90px;
    border-radius: 50%;
    display: block;
    margin: 15px 0;
}
```

### Useful Resources

- [Frontend Mentor](https://www.frontendmentor.io)
- [MDN Web Docs - CSS Transitions](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_transitions/Using_CSS_transitions)

---

## Author

- GitHub - [Mo-boop-ux](https://github.com/Mo-boop-ux)
- Frontend Mentor - [@Mo-boop-ux](https://www.frontendmentor.io/profile/Mo-boop-ux)
