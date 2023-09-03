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

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Desktop Image](images/product.png)

### Links

- Solution URL: [Solution](https://github.com/Fejiro001/product-preview-card-component-main)
- Live Site URL: [Live Site](https://fejiro001.github.io/product-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- Mobile-first workflow

### What I learned
Having 2 equal divs side by side in one div container. Code is shown below:

```css
.productCard {
  background-color: hsl(0, 0%, 100%);
  display: flex;
  flex-direction: row;
  width: 40rem;
  min-height: 25rem;
  border-radius: 0.5rem;
  margin: 2rem;
}

.productImg {
  flex: 50%;
  background: url(images/image-product-desktop.jpg) center/cover no-repeat;
  max-width: 100%;
  border-radius: 0.5rem 0 0 0.5rem;
}

.productInfo {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  flex: 45%;
  padding: 5%; /*Border-box=> 45%+5%=50%*/
  word-wrap: break-word;
}
```

### Continued development

I need to practice more with image scaling on different devices

### Useful resources

- [Add Icon to Button with CSS](https://stackoverflow.com/a/49997979) - This helped me know how to add an icon to a button using css
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

## Author

- Frontend Mentor - [@Fejiro001](https://www.frontendmentor.io/profile/Fejiro001)
- Twitter - [@aberefejiro](https://www.twitter.com/aberefejiro)
