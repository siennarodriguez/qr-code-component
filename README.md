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
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![](/images/Screenshot%202024-01-24%20at%2014-11-33%20Frontend%20Mentor%20QR%20code%20component.png)

### Links

- Solution URL: [https://github.com/siennarodriguez/qr-code-component](https://github.com/siennarodriguez/qr-code-component)
- Live Site URL: [https://srodriguez-qr-code-component.netlify.app/](https://srodriguez-qr-code-component.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

I found it difficult to center the body and card and found myself overcomplicating things on the page. But I managed to find a working solution in the end using flexbox.

```css
body {
    background-color: hsl(212, 45%, 89%);
    font-family: 'Outfit', sans-serif;
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
}
```

### Continued development

In future projects, I would like to practice and refine how to use Flexbox, CSS grid and the Nested Layouts Technique.

### Useful resources

- [HTML CSS REFERENCE](https://supersimpledev.github.io/references/html-css-reference.pdf) - This helped me as a quick point of reference for HTML and CSS

## Author

- Frontend Mentor - [@siennarodriguez](https://www.frontendmentor.io/profile/siennarodriguez)
- LinkedIn - [Sienna Ridriguez](https://www.linkedin.com/in/siennamrodriguez/)

## Acknowledgments

I found myself stuck with centering the container card and found this video helpful - [QR Code Component | Frontend Mentor Challenge | Day 11](https://www.youtube.com/watch?v=5BBYPntB-GY&ab_channel=MrCoder)