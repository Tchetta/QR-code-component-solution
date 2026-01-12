# Frontend Mentor - QR Code Component

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

## Overview
A mobile-first QR code component built with a focus on professional SCSS architecture and BEM naming conventions.

## Vercel Site
[https://qr-code-component-solution-lime.vercel.app/](https://qr-code-component-solution-lime.vercel.app/)

## My Process
### Built With
- Semantic HTML5
- BEM Methodology
- SCSS 7-1 Pattern

### What I Learned
I resolved a common clipping issue where images ignore a parent's `border-radius`. By setting `display: block` on the image to remove inline whitespace and ensuring `height: 100%` with `object-fit: cover`, the image perfectly obeys the `overflow: hidden` container.

```scss
&__image-box {
    width: 100%;
    border-radius: abs.rem(10);
    overflow: hidden;
}

&__image {
    height: 100%;
    object-fit: cover;
}

```

## Deployment
Hosted on Vercel. Note: `.gitignore` is configured to prevent SCSS source/map bloat while keeping the production `dist/` folder clean.

## Author
Frontend Mentor - [@Tchetta](https://www.frontendmentor.io/profile/Tchetta)