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
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](/assets/images/website%20ss.png)

### Links

- Solution URL: (https://www.frontendmentor.io/solutions/social-links-profile-using-transitions-YUaVjglXc4)
- Live Site URL: (https://aishi-jain.github.io/Social-Links-Profile/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Transitions and Transformations


### What I learned

In this project, I learned how to create a simple, responsive profile card that includes social media links. I reinforced my skills in:

- Structuring HTML for accessibility
- Using CSS Flexbox for layout
- Implementing responsive design techniques
- Using transitions and transformations to bring more life to the design

Here's the snippet of the code I wrote for making the social links buttons look alive: 

```css
ul a {
    display: block;
    padding: 10px;
    width: 270px;
    height: 40px;
    color: var(--White);
    font-weight: 700;
    font-size: 14px;
    border-radius: 8px;
    background-color: var(--grey);
    transition: background-color 0.5s ease, color 0.5s ease, transform 0.5s cubic-bezier(0.25, 0.8, 0.25, 1);
}

ul a:hover {
    background-color: var(--green);
    color: var(--off-black);
    transform: scale(1.2);
}
```

### Continued development

For future development, I plan to:

- Add animations and transitions to enhance user experience
- Implement a dark mode toggle
- Explore integrating with a backend to dynamically load profile data

## Author

- Frontend Mentor - [@Aishi-Jain](https://www.frontendmentor.io/profile/Aishi-Jain)
- LinkedIn - [Aishi Jain](https://www.linkedin.com/in/aishi-jain-367758267/) 
