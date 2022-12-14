# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Product preview card component solution](#frontend-mentor---product-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
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

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![desktop](/screenshot/desktop_screenshot.png)

![mobile](/screenshot/mobile_screenshot.png)

### Links

- Solution URL: [https://github.com/changhoji/product-preview-card-component](https://github.com/changhoji/product-preview-card-component)
- Live Site URL: [https://changhoji.github.io/product-preview-card-component/](https://changhoji.github.io/product-preview-card-component/)

## My process

### Built with

- HTML
- CSS

### What I learned

```html
<picture class="product-image">
  <source media="(min-width: 768px)" srcset="url">
  <source media="(max-width: 768px)" srcset="url">
  <img src="url">
</picture>
```
picture tag in HTML works like if statement in C/Python/Java, ...

From the top, It'll check one by one and bring up images that satisfy conditon. If no source tags satisfy conditon, img tag which places in the last line will be excuted.

### Continued development

- CSS grid using flex
- Responsive Web Design
- HTML code easy to read
- Appropriate value about Class & Id

### Useful resources

- [opentutorials-css-flex](https://opentutorials.org/course/2418/13526) - This helped me for flex grid. It's so usefule to make layout and I'll use it going forward.
- [html-tag-picture](https://velog.io/@korea_webclass/css-picture) - This helped me for picture tag for responsive web design. 

## Author

- Github - [ChangHo Lee](https://github.com/changhoji)
- Frontend Mentor - [changhoji](https://www.frontendmentor.io/profile/changhoji)
