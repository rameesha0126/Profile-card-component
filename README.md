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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot 

[Mobile View](https://github.com/rameesha0126/Profile-card-component/blob/master/Mobile-view.png)
[Desktop View](https://github.com/rameesha0126/Profile-card-component/blob/master/Desktop-view.png)

### Links

- Solution URL: [Solution URL](https://github.com/rameesha0126/Profile-card-component.git)
- Live Site URL: [Live Site URL](https://rameesha0126.github.io/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

- Using variables to save the colors and use in the CSS code. 
```css 
:root {
    --Dark-cyan: hsl(185, 75%, 39%);
    --Very-dark-desaturated-blue: hsl(229, 23%, 23%);
    --Dark-grayish-blue: hsl(227, 10%, 46%);
    --Dark-gray: hsl(0, 0%, 69%);
}
```

- Using "position: relative" and "top:" attributes to place the profile picture against the document flow.  

```css 
.profile-picture {
    position: relative;
    top: -2.75em;
    border-radius: 50%;
    max-width: 100%;
    height: auto;
    border: 0.3em solid hsl(0, 0%, 100%);
}
```

### Continued development

Learning about using and manipulating images to create a continuous background. 

### Useful resources

- [W3schools CSS Tutorial](https://www.w3schools.com/css/default.asp)

## Author

- Github - [Rameesha0126](https://github.com/rameesha0126)
- Frontend Mentor - [@rameesha0126](https://www.frontendmentor.io/profile/rameesha0126)
