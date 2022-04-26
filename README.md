# Frontend Mentor - NFT preview card component solution

The solution to the challenge provided by frontend mentor: [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenge helped me develop through the basics of html/css for building realistic projects. 

## Table of contents

- [Overview](#overview)
- [The challenge](#the-challenge)
- [Screenshot](#screenshot)
- [My process](#my-process)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Useful resources](#useful-resources)
- [Author](#author)



## Overview

The use of proper html tags and styling using css help me incresed the real time eperience with real world projects.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./design/Screenshot%20.png)


## My process

First started coding in html using semantic html in visual studio code creating main function under that four classes with sub classes and images 'img' tag in order to complete the challenge. based on the description provided followed the process. After coding in html now we need to add styling for web page to look attractive. create a style.css file add css grid, properties root, html, body and each division proper color, size and background. After styling part add the external link in html to access the style.css file. go live share for better performance. 

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Styled Components](https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600&display=swap) - For styles


### What I learned

While working on this project, I learned the use of icons and focued elements (active state) 

```html
<div class="e-container">
        <img class="icon-view" src="./images/icon-view.svg" alt="eye icon">
      </div>
```
```css
.container .e-container:hover {
    cursor: pointer;
    background-image: linear-gradient(var(--cyan-container), var(--cyan-container)), url(./images/image-equilibrium.jpg);
}
.container .e-container .icon-view {
    visibility: hidden;
}
.container .e-container:hover .icon-view{
    visibility: visible;
}
```

### Useful resources

- [w3 schools](https://www.w3schools.com/howto/howto_css_cards.asp) 

## Author

- Frontend Mentor - [@S-anas](https://www.frontendmentor.io/profile/S-anas)


