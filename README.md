# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./design/destkop-design.jpg)


### Links

- Solution URL: https://www.frontendmentor.io/solutions/social-link-card-challenge-using-flexbox-nbo3IiMeRe
- Live Site URL: https://pete13232.github.io/Social-link-card-challenge/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

- Applied Flexbox and the gap property to build well-structured, maintainable layouts without relying heavily on margins and padding.

- Implemented simple interactive animations and transitions to enhance UI responsiveness and user experience.

```html
<div id="card">
      <div id="card-header">
        <img src="assets/images/avatar-jessica.jpeg" alt="">
        <div class="header">
          <h1>Jessica Randall</h1>
          <p class="highlight-text">London, United Kingdom</p>
        </div>
        <p>"Front-end developer and avid reader."</p>
      </div>
      <div id="card-button">
        <button><a href="">GitHub</a></button>
        <button><a href="">Frontend Mentor</a></button>
        <button><a href="">LinkedIn</a></button>
        <button><a href="">Twitter</a></button>
        <button><a href="">Instagram</a></button>
      </div>
    </div>
```

```css
#card-header, #card-button {
    display: flex;
    flex-direction: column;
    align-items: center;
}

#card-header {
    gap: 24px
}

#card-button {
    gap: 10px;
    margin: 30px 0 10px 0;
}
```

## Author
- Frontend Mentor - [@pete13232](https://www.frontendmentor.io/profile/pete13232)
- Github - [@pete13232](https://github.com/pete13232)
