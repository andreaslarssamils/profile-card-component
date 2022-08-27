# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)

  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

  - [Useful resources](#useful-resources)

- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

This is my solution on the Profile Card Component

### The challenge

- Build out the project to the designs provided

### Screenshot

![](./images/screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

Iv'e been using HTML and CSS, I was struggeling to get the positioning of the circles right. So any inputs on how to improve the positioning highly appriciated.

### Built with

- HTML5
- CSS
- Flexbox

### What I learned

Ive learned how to center absolute elements. I was using this technique, left and right 50% and transform translate to balance it.

```css
.profile-pic img {
  position: absolute;
  width: 96px;
  height: 96px;
  border-radius: 50%;
  border: 5px solid white;
  margin: 0 auto 0 auto;
  top: 150px;
  left: 50%;
  right: 50%;
  transform: translate(-50%, -50%);
}
```

### Useful resources

- [How to position absolute element](https://stackoverflow.com/questions/1776915/how-can-i-center-an-absolutely-positioned-element-in-a-div) - This helped me to position absolute element.

## Author

- Frontend Mentor - [@andreaslarssamils](https://www.frontendmentor.io/profile/andreaslarssamils)

## Acknowledgments

Thank you Frontend Mentor
