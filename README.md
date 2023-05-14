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
- [Acknowledgments](#acknowledgments)

## Overview

This profile card consists of a banner image, profile info and stats sections.

### The challenge

- Build out the project to the designs provided

### Screenshot

![](./assets/images/live-screenshot.png)

### Links

- [Solution](https://your-solution-url.com)
- [Live Site](https://stk-profile-card.netlify.app/)

## My process

I made this card using Flexbox. There are two main divs, the profile info and profile stats divs. The profile info div showcases the profile's basic details including name, age and location. The profile stats div showcases the profile's follower, like and photo count.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

CSS Positioning.

```css
.stats__row {
  display: flex;
  justify-content: space-around;
  align-items: center;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 100%;
  height: 100%; 
}
```

### Continued development

I hope to continue learning Flexbox.

### Useful resources

- [ChatGPT](https://chat.openai.com) - This bot is super amazing, it helped me with the transform() function!

## Author

- Frontend Mentor - [@shinthantkn](https://www.frontendmentor.io/profile/shinthantkn)
- Twitter - [@shinfluencer](https://www.twitter.com/shinfluencer)

## Acknowledgments

ChatGPT helped me a bit, I'm so thankful to OpenAI!
