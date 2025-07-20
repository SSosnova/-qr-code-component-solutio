# -qr-code-component-solution
 QR Code Component Solution
# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help me improve my coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Author](#author)

## Overview

### Screenshot

![Screenshot of the QR code component solution](./qr-component-screenshot.jpeg)

**Note:** Replace `./screenshot.png` with the actual path and filename of your screenshot (e.g., `./images/qr-code-component-screenshot.jpg`).

### Links

- Solution URL: [Add your GitHub Repository URL here](https://github.com/your-username/qr-code-component-solution)
- Live Site URL: [Add your Live Site URL here](https://your-username.github.io/qr-code-component-solution/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (using `var()` for consistent styling)
- Flexbox (for centering the component on the page)
- Mobile-first workflow (considering smaller screens first)

**Note:** I removed CSS Grid, React, Next.js, and Styled Components from the list as they were not used in this particular solution.

### What I learned

This project was a great refresher on fundamental HTML and CSS concepts. I particularly focused on:

- **Semantic HTML:** Ensuring the use of appropriate tags like `<h2>` and `<p>` within the card structure.
- **CSS Variables (`var()`):** Reinforcing the benefits of defining colors and font properties in a `:root` scope for easy management and consistency, as learned with the `hsl` color format.
- **Flexbox for Layout:** Solidifying the understanding of `display: flex`, `justify-content: center`, and `align-items: center` to perfectly center the component on the page, both horizontally and vertically.
- **Responsive Images:** Ensuring the `<img>` tag correctly scales within its container using `width: 100%` and has rounded corners with `border-radius`.
- **`box-sizing: border-box;`:** Understanding its importance in simplifying layout calculations by including padding and border within an element's defined width and height.

```html
<div class="qr-code-card">
    <img src="image-qr-code.png" alt="QR Code to Frontend Mentor" class="qr-code-image">
    <h2 class="card-title">Improve your front-end skills by building projects</h2>
    <p class="card-description">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
</div>
