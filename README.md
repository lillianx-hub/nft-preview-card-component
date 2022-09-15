# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](/images/Screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/nftpreviewcardcmoponent-9AMtfX8CHS)
- Live Site URL: [Add live site URL here](https://benevolent-hamster-e41dfc.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

To see how you can add code snippets, see below:

```HTML5
<div class="card-img">
  <img class="nft" src="images/image-equilibrium.jpg">
    <div class="hover">
      <img src="images/icon-view.svg" alt="">
    </div>
</div>
```

```css
.card-img img {
  max-width: 100%;
  border-radius: 8px;
}

.card .card-img {
  position: relative;
}

.card .card-img .hover {
  position: absolute;
  top: 0;
  background-color: hsl(178, 100%, 50%, 60%);
  width: 100%;
  height: 300px;
  z-index: 999;
  opacity: 0;
  overflow: hidden;
  border-radius: 8px;
  transition: opacity 0.5s  ease-in-out;
}

.card .card-img .hover img {
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate( -50%, -50%);
}

.card .card-img .hover:hover {
  opacity: 1;
  cursor: pointer;
}
```

### Continued development

Do more challenge

### Useful resources

- [Example resource 1](https://www.w3schools.com/cssref/css3_pr_box-shadow.asp) - This helped me for css shadow reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.w3schools.com/cssref/default.asp) - This is an amazing article which helped me finally understand css . I'd recommend it to anyone still learning this concept.


## Author

- Frontend Mentor - [@lillianx-hub](https://www.frontendmentor.io/profile/lillianx-hub)
- Twitter - [@lillianxhub](https://www.twitter.com/lillianxhub)

## Acknowledgments

a hover css html markdown 
