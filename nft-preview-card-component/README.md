# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - NFT preview card component solution](#frontend-mentor---nft-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
  - [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](screenshot.ppg)

### Links

- Solution URL: [Frontend Mentor](https://your-solution-url.com)
- Live Site URL: [Vercel](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox

### What I learned

I learned how to manipulate transitions and all the hover states. I also learned how to position an element on top of another element by using the CSS position property as such: 

```html
<div class="hero-image-container">
    <img src="/images/image-equilibrium.jpg" alt="" aria-hidden="true" class="hero-image">
    <div class="hero-image-filter-container">
        <img src="/images/icon-view.svg" alt="" aria-hidden="true" class="hero-image-filter">
    </div>
</div>
```
```css
/* ? Hero Image Styles */
.container .hero-image-container {
    position: relative;
}
.container .hero-image-container .hero-image {
    border-radius: 15px;
    width: 100%;
}
.container .hero-image-filter-container{
    position: absolute; 
    display: flex;
    justify-content: center;
    align-items: center;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border-radius: 15px;
    opacity: 0;
    cursor: pointer;
    background-color: hsla(178, 100%, 50%, 0.5);
    transition: all 0.3s ease-out;
}
```
I also learned how to style an HR tag and how to center elements effectively by using CSS flexbox for the .container elements and using min-height: 100vh for the body element itself to center the .container 

### Continued development

I will delve into CSS trasitions and animations so I can implement them more effectively in my next projects. I also want to revisit CSS positioning since I spent a lot of time on figuring out how to have the hover state work for the hero image. 

## Author

- Website - [Justin Vera](https://www.justinvera.com)
- Frontend Mentor - [@justinnvera](https://www.frontendmentor.io/profile/justinnvera)
