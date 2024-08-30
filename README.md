# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ).

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

![](./desktop-active-preview.png)

### Links

- Solution URL: [Code](https://github.com/hellcsaba/social-links-profile)
- Live Site URL: [Social Links Profile Live](https://hellcsaba.github.io/social-links-profile/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow
- CSS Transitions

### What I learned

I learnt how to make custom links and how to use CSS Grid to center a component in a screen. I also tried out how to make a simple transition for the custom links. I think it provides a better UX.

```css
a {
  background-color: var(--grey700);
  color: var(--white);
  text-decoration: none;
  padding: 1rem;
  min-width: 20rem;
  border-radius: 10px;
  font-weight: 600;
  transition: background-color 0.25s ease-in 0.05s, color 0.25s ease-in 0.05s;
}
```

When the event is triggered the transition starts after 0.05s delay and the ease-in transition takes 0.25s. The transition applies to the background-color and the color (of the text).

## Author

- Website - [Csaba Hell](https://github.com/hellcsaba)
- Frontend Mentor - [@hellcsaba](https://www.frontendmentor.io/profile/hellcsaba)
- LinkedIn - [@csabahell](https://www.linkedin.com/in/csabahell/)
