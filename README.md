# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![desktop](./images/Screen%20Shot%201024px.png)
![small mobile](./images/Screen%20Shot%20375px.png.png)

### Links

- GITHUB URL: [https://github.com/Slam256/17-day-frontend](https://github.com/Slam256/17-day-frontend)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
I started with the desktop view and then designed the other viewports. 

Looking at the image provided, I drew up a rough sketch of how the HTML would look like based on how the component is structured.
### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned

proud of my use of CSS variable. Helped in consistency of the colors provided.

```css
:root{
--main-background: hsl(233, 47%, 7%);
--card-background: hsl(244, 38%, 16%);
--accent: hsl(277, 64%, 61%);
--neutral-white: hsl(0, 0%, 100%);
--transparent-white-one: hsla(0, 0%, 100%, 0.75);
--transparent-white-two: hsla(0, 0%, 100%, 0.6);
}
```
I am also proud of the use of pseudo-classes here.
```css
.card-img::after {
    position: absolute;
    content: '';
    height: 100%;
    width: 100%;
    left: 0;
    top: 0;
    background-color: hsla(277, 64%, 61%, 0.6);
    
}
```
There could have been a better way. Came across this using MDN.

### Continued development

Would like to use libraries the next time i design this instead of Html and css alone.

## Author

- Twitter - [@stacieslam](https://www.twitter.com/stacieslam)




