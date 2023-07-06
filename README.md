<<<<<<< HEAD
# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
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

![](./images/Screenshot.jpg)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Git and Github


### What I learned

I was struggling to find a way to put the main image with the hover effect using the second image and also the background-color. I managed to do it althoug i am aware it's not the best coding practice. I will try to improve it ASAP.

The process is like this code above and I am kind of proud I could make it work.

```html
<div class="image-container">
  <img class="ethereum-img" src="./images/image-equilibrium.jpg">
  <img class="view-img" src="./images/icon-view.svg">
</div> 
```
```css
.image-container{
	position: relative;
	top: 0;
	left: 0;
}

.image-container:hover{
	background-image: url(./images/icon-view.svg) center no-repeat;
	cursor:pointer;
}

.image-container .ethereum-img{
	border-radius: 10px;
	width: 100%;
	position: relative;
}

.image-container:hover .view-img{
	display:inline-block;
}

.view-img{
	position: absolute;
	left:0;
	display:none;
	padding: 125px;
	border-radius: 10px;
	background-color: hsla(178, 100%, 50%,0.5);
}
```

### Continued development

As I said I'll try to implement as soon as possible a more profeional way to put the hover effect on the image.

## Author

- Github - [LetsGetToCode](https://github.com/letsGetToCode)
- Frontend Mentor - [@letsGetToCode](https://www.frontendmentor.io/home)

=======
# nftPreviewCard

## State of Art
- I am strugling to find a way to how the view image when hover over the main image. I'll return back to this project soon and hope I can finish it.
>>>>>>> b3467b34d7691c66d433e5e9a56ea4ba8e4e8d26
