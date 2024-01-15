# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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



## Overview
A cart of prefume product card for desktop and various display on different devices 

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot.jpg)
screenshots for both desktop and mobile display are in the floder named screenshots

### Links

- Solution URL: [https://github.com/Geokobby/product-preview-card-component-main]
- Live Site URL: [https://geokobby.github.io/product-preview-card-component-main/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox




### What I learned

learn how to occupy and replace the image of the product on multiple screens(devices) using the `background-image:url();` property 

```html
<div  class="image__replacement"
      ></div>
```
```css
.image__replacement{ background-image: url(images/image-product-desktop.jpg);
}
```
```media query .image__replacement{ url(images/image-product-mobile.jpg);
}
```


### Continued development
Would like to focus more and JS and get familiar with it syntax 
### Useful resources

Help with the background image swap from the desktop to various screen displays "devices" (https://www.youtube.com/watch?v=S10yhgq0BtM)

## Author

- Frontend Mentor - [@Geokobby](https://www.frontendmentor.io/profile/Geokobby)
- Twitter - [@Geokobby_](https://twitter.com/Geokobby_)



## Acknowledgments
