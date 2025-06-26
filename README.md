# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: https://qr-code-frontendmentor-hanna.netlify.app/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

In this project, I learned when to use display block, inline, grid, and flex. In this case, I used display flex and set the flex direction to column because if you look at the design preview, it looks like a single column layout.

Besides display, I also learned how to make a responsive design, so the website will adjust to fit both mobile and desktop screen sizes.

```css
section {
    display: flex;
    flex-direction: column;
    background: var(--white);
    width: 300px;
    margin: 10rem auto;
    padding: 1rem;
    border-radius: 20px;
    box-shadow: 0 1rem 1rem rgba(69, 76, 83, 0.1);
}

@media (max-width: 720px) {
    section {
        margin: 6rem auto;
    }
}
```

### Continued development

I still need to learn more about grid, because it's a bit tricky compared to flexbox.

### Useful resources

- [stackoverflow](https://stackoverflow.com/questions/48714783/cant-center-a-section-in-css) - This helped me to center the QR code section.

## Author

Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)