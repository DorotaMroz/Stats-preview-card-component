# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size

### Screenshot

![](images/ScreenshotDesktop.jpg)

### Links

- Solution URL: (https://github.com/DorotaMroz/Stats-preview-card-component/blob/main/README.md)
- Live Site URL: (https://dorotamroz.github.io/Stats-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

```html
<p class="text-spacing1"><span class="number">10k+</span>COMPANIES</p>
```
```css
.row {
    display: flex;
    align-items: center;
    justify-content: center;
    margin: auto;
}

body {
   font-family: var(--body-font);
   background-color: var(--main-background);
   /* center whole card using flex-box on the body
      perfectly centered in any screen sizes!
    */
   display: flex;
   justify-content: center;
   align-items: center;
   /* component will be fully centered, since your body has a min-height of the full screen of the browser!
    */
   min-height: 100vh;
}

.image-container {
    /* turn black and white image to color*/
    background-color: var(--soft-violet);
    border-radius: 0 .5rem .5rem 0;
}

img {
    display: flex;
    width: 31rem;
    height: 26.3rem;
    object-fit: cover;
    /* turn black and white image to color*/
    mix-blend-mode: multiply;
    opacity: 75%;
}
```
### Continued development

I'm still not completely comfortable with positioning, flexbox and grid techniques.

### Useful resources

- [Example resource 1]([https://www.example.com](https://www.w3schools.com/cssref/tryit.asp?filename=trycss_mix-blend-mode))
This helped me with turning black and white image to color. 
The mix-blend-mode property specifies how an element's content should blend with its background.

## Author

- Website - [Dorota Mroz]
- Frontend Mentor - [@DorotaMroz](https://www.frontendmentor.io/profile/DorotaMroz)

## Acknowledgments

It will be difficult to respond and solve problems without any support from the other web developers.
Thank you for your support. I appreciate you.

@DavidMorgade
@correlucas

