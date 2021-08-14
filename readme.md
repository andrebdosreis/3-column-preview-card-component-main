# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.png)


### Links

- [Solution URL](https://github.com/andrebdosreis/3-column-preview-card-component-main)
- [Live Site URL](https://andrebdosreis.github.io/3-column-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

• I learned how to use and organize variables in CSS code:
```css
:root {
    --pri-bright-orange: hsl(31, 77%, 52%);
    --pri-dark-cyan: hsl(184, 100%, 22%);
    --pri-very-dark-cyan: hsl(179, 100%, 13%);
    --neu-transp-white: hsl(0, 0%, 100%, 0.75); /*paragraphs*/
    --neu-very-light-gray: hsl(0, 0%, 95%); /*bg, heading, btn*/
}
```

• I learned how to apply first-child and last-child in CSS items to apply border-radius correctly:
```css
.card:first-child{border-radius: 10px 0 0 10px;}
.card:last-child{border-radius: 0 10px 10px 0;}
```

### Useful resources

- [B7 Web](https://www.b7web.com.br) - B7Web is an online web developer course from Brazil. So i learned how to write HTML and CSS codes studying B7Web's classes.

## Author

- Website - [André dos Reis](https://www.andredosreis.com.br)
- Frontend Mentor - [@andrebdosreis](https://www.frontendmentor.io/profile/andrebdosreis)
- Twitter - [@andrebdosreis](https://www.twitter.com/andrebdosreis)

## Acknowledgments

Thanks FrontEndMentor.io for challenge. I'm learning a lot with you.

