# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Github Repo URL: [QR Code Repo](https://github.com/amyspencerproject/order-summary-component)
- Live Site URL: [QR Code Page](https://amyspencerproject.github.io/order-summary-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS Variables
- CSS Grid
- Mobile-first workflow

### What I learned

- For the background image I first went too complicated. I was trying to use a psuedo class and positioning and just making it more complicated than necessary. Just setting a background image with no-repeat did the trick very simply!
- I chose to use flex for the plan info. At first I used margins to force the music note icon and the plan/price to stay closer together. I started to play with flex shrink and grow to get the same effect. I used a `gap: 1rem` in the plan-details-container and a `flex-grow: 1` for the middle element with the plan title and price.
- Since this is just a component and not meant to be an entire page I wondered if I should be using an `<h1>` heading or any heading for that matter.
- Why did I use button vs CTA link?

### Continued development

### Useful resources

- [Box-shadowing](https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow) - guide for positioning of shadown and depth of blur
- [Background Images](https://developer.mozilla.org/en-US/docs/Web/CSS/background) - guide for all the variables when setting a background image
- [Flex-grow](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-grow)
- [Flex-gap](https://developer.mozilla.org/en-US/docs/Web/CSS/gap)

## Author

- Website - [Amy Spencer](https://spencerproject.com/)
- Frontend Mentor - [@amyspencerproject](https://www.frontendmentor.io/profile/amyspencerproject)
- Linkedin - [amyspencercodes](https://www.linkedin.com/in/amyspencercodes/)
