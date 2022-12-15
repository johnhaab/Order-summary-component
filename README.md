# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
- [Author](#author)

## Overview

It has been 9 days sicne ( started learning HTML and CSS and it is getting a lot easier.

### Screenshot

![](final.png)

### Links

- Solution URL: [Click me!](https://www.frontendmentor.io/solutions/nft-preview-card-component-E8e3-FcAJY)
- Live Site URL: [Click me!](https://johnhaab.github.io/NFT-preview-card-component/)

## My process

First I started with adding what I need in index.html to get everything working, then worked in styles.css.

### Built with

- HTML5 markup
- CSS custom properties

Code snippets, see below:

```html
<body>

  <div class="card">

    <div class="image">
      <img src="images/image-equilibrium.jpg" alt="A photo" class="mainimg">
      <div>
        <img src="images/icon-view.svg" alt="#">
      </div>
    </div>

        <h3>Equilibrium #3429</h3>

      <div class="desc">
        Our Equilibrium collection promotes balance and calm.
      </div>

      <div class="price-time">
       <div class="price">
        <img src="images/icon-ethereum.svg" alt="" class="icon">
        0.041 ETH
       </div>
     <div class="time">
      <img src="images/icon-clock.svg" alt=""/>
        3 days left
     </div>
    </div> 

     <div class="creator">
        <img src="images/image-avatar.png" alt="" class="avi">
         Creation of <span>Jules Wyvern</span>
     </div>
     </div>
</body>
```
```css
.image div{
    position: absolute;
    background-color: hsl(178, 100%, 50% );;
    top: 0;
    width: 100%;
    height: 100%;
    opacity: 0; 
}

.image div img {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}

.image div:hover {
    opacity: 1;
    cursor: pointer;
    border-radius: 10px;
}
```

## Author

- Frontend Mentor - [@johnhaab](https://www.frontendmentor.io/profile/johnhaab)
- Twitter - [@johnlhaab](https://www.twitter.com/johnlhaab)
