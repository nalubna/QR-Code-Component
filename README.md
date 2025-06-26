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

- Solution URL: [My Solution](https://www.frontendmentor.io/solutions/responsive-qr-code-site-using-css-flexbox-K6QYFWH2e2)
- Live Site URL: [My QR Code Website](https://qr-code-frontendmentor-hanna.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS flexbox

### What I learned

I learned when to use display block, inline, grid, and flex. And in this case, I used display flex and set the flex direction to column.

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

I still need to learn more about CSS grid, because it's a bit tricky compared to flexbox.

### Useful resources

- [Stackoverflow](https://stackoverflow.com/questions/48714783/cant-center-a-section-in-css) - This site helped me to center the QR code section
- [Zero to Mastery](https://zerotomastery.io/blog/css-grid-vs-flexbox/#How-CSS-Grid-handles-layout-control) - This site enlighten me about CSS grid and flexbox

## Author

Frontend Mentor - [@HannaNashita](https://www.frontendmentor.io/profile/hannanashita)