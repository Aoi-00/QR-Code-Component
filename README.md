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


## Overview
A simple first project on designing a QR component through CSS and HTML.

### Screenshot
![desktop screenshot](./screenshots/desktop.png)
![mobile screenshot](./screenshots/mobile.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

**Note: TBA**

## My process
- Made the divs to segregate the components (paragraph, text, card, qrcode img)
- Added background to body
- Added font styling, sizing & colors (based on design specification)
- Get the design format layout out
- Edit minor smaller details (padding/margin/box-shadow/media query) to finish up

### Built with
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Google Font (Outfit)

### What I learned
Was a good first practice of flexbox after watching tutorials. Add display:flex, flex-direction and justify/align to the parent element (eg container in this case) to control the flex!
Hide scrollbar with overflow!

```css
.container {
    display: flex;
    width: 100%;
    height: 100%;
    background-size: cover;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}
.body  {
    background:rgba(213,225,239,255);
    height: 100vh;
    overflow: hidden; /*Hide scrollbar*/
}
```
### Continued development
Need to explore more on box-shadow, and border-radius. Still cannot replicate the nice borders of the images. And more general practice on CSS.


### Useful resources
- [w3schools](https://www.w3schools.com/) - This helped me find specific syntax for CSS styling as I am still relative new to this and do not know the properties and values well.

## Author
- Frontend Mentor - [@Aoi-00](https://www.frontendmentor.io/profile/Aoi-00)
