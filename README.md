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
- [Acknowledgments](#acknowledgments)


## Overview

### Screenshot

![](./img/screenshot.jpeg)

### Links

- Live Site URL: [See the demo on Github Pages](https://jimi-s-frontend-mentor-cs.github.io/QR-Code-Component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### Continued development

I still have some troubles resizing images inside a flexbox container. I am sure there should be some better way than my implementation, so if you have any suggestion feel free to write me :)

Right now I resize the image inside the container by doing so

```css
.qr-code {
    width: 100%;
}
```
but I find kinda redundant to set a 100% width (since I thought 100% was the default if you don't set it).
Again, I am sure there is a better way to do this, I just can't figure which...


I also don't know if there is a better way to keep a component size consistent without using the ```max-width``` css selector.

I use 
```css
.container {
    max-width: 25em;
}
```

to set the maximum size of the main container. While it looks fine when you resize, I don't know if this is an actual good practice to make a component look good inside a page no matter the screen resolution.


### Useful resources

- [Kevin Powell](https://www.youtube.com/kepowob) - This amazing guy helped me A TON getting me back into Web Development, refreshing by knowledge and also teaching me new stuffs and tricks (especially with CSS and flexbox).

## Author

- Frontend Mentor - [@JimiIT92](https://www.frontendmentor.io/profile/JimiIT92)


## Acknowledgments

Big shoutout to [Kevin Powell](https://www.youtube.com/kepowob) for sharing his resources to the public, so other developers like me can learn new stuff!