# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the interface depending on their device's screen size

### Screenshot

<table>
    <tr>
        <th>Desktop (Large screens)</th>
        <td><img src="./results/desktop.png"></td>
    </tr>
    <tr>
        <th>Tablet (Medium screens)</th>
        <td><img src="./results/tablet.png"></td>
    </tr>
    <tr>
        <th>Mobile (Small screens)</th>
        <td><img src="./results/mobile.png"></td>
    </tr>
</table>

### Links

- [Live Site URL](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS Grid
- CSS Grid Template Areas

### What I learned

#### CSS Grid Template Areas

```css
.grid-container {
    display: grid;
    grid-template-areas:
        'card1 card2 card2 card3'
        'card1 card2 card2 card3'
        'card1 card2 card2 card3'
        'card1 card2 card2 card3'
        'card1 card5 card6 card3'
        'card4 card5 card6 card3'
        'card4 card5 card6 card3'
        'card4 card7 card8 card8'
        'card4 card7 card8 card8'
        'card4 card7 card8 card8';
    grid-auto-columns: 1fr;
    grid-auto-rows: 1fr;
    gap: 25px;
}
```
- ```grid-template-areas``` specifies how to display columns and rows, using named grid items.
- ```grid-auto-columns``` specifies width for each column. The value ```1fr``` makes all columns the same size.
- ```grid-auto-rows``` specifies height for each row. The value ```1fr``` makes all rows the same size.

### Continued development

I feel like more can be done to make sizes and spacing more accurate.

### Useful resources

- [CSS Grid Layout](https://www.w3schools.com/css/css_grid.asp) - This helped to understand CSS grids.
- [CSS Media Queries](https://www.w3schools.com/css/css3_mediaqueries_ex.asp) - This helped to understand how to adapt the design to different screen sizes.
- [Bootstrap Breakpoints](https://getbootstrap.com/docs/5.2/layout/breakpoints/) - Although I didn't use Boostrap, this article helped me to understand how to manage breakpoints for each type of device.

## Author

- Frontend Mentor - [@KarenNR](https://www.frontendmentor.io/profile/KarenNR)