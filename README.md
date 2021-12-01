# Frontend Mentor - Four card feature section solution


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

- This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

### The challenge

- Build it to look as close as possible to the design provided.

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![desktop-preview](https://user-images.githubusercontent.com/49578782/144166804-cbc7d9ce-8935-44b3-a614-da68156a1634.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

-Started with mobile design first than use media queries for desktop layout, created variables for colors and fonts.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow


### What I learned

- This is my second grid project, i learned how to create layout like this using grid areas. 


```css
.card__container {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        grid-template-rows: repeat(4, auto);
        gap: 1.5rem;
        grid-template-areas:
          ".     card2     ."
          "card1 card2 card3"
          "card1 card4 card3"
          ".     card4     .";
    }
```

### Continued development

- Continue to learn grid in order to improve my skills so i can build more complex layouts for my next challenges 


### Useful resources

- [Example resource ](https://developer.mozilla.org/en-US/) 



## Author

- Frontend Mentor - [@Dblack84](https://www.frontendmentor.io/profile/Dblack84)
- Twitter - [@D_Black84](https://www.twitter.com/D_Black84)

