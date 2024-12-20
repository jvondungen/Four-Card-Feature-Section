# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
Create a 4-card feature section webpage that was responsive. The layout was a single column in mobile view and 3-column grid in desktop view. 

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![./screenshot.jpg] [./Screenshot-mobile.png]
  
### Links

- Solution URL: [https://github.com/jvondungen/Four-Card-Feature-Section]
- Live Site URL: [https://jvondungen.github.io/Four-Card-Feature-Section/]

## My process
I began with HTML and then began the CSS styling in the mobile first. I used the grid display for the first time and the single column worked easily. Then I added the @media queries to transform the display view to 3 columns. This part was really challenging, since I couldn't get the 1st and 3rd column cards to center align with the two center column cards. I played around with this for awhile, adding grid-areas. Finally, thanks to "mdn web docs_" I realized I needed to add a space " . " to my areas and then it worked!

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned to use the Grid display and build a responsive page.


### Continued development

I'd like to continue practice with the grid layout. I'll seek out more designs where I can use this feature. 

### Useful resources

- [mdn web docs_](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/) - Grids. Outlined parameters for grid-areas, particulary spaces and defined how to leave a space. This helped was the game changer for me! Not sure why I didn't read it at the start. 
- [Josh w Comeau](https://www.joshwcomeau.com/css/interactive-guide-to-grid/) - Interactive Guide to Grid. This is where I started and gave me a great overview of grid display.


## Author

- Frontend Mentor - [https://www.frontendmentor.io/profile/jvondungen]
- Github [https://github.com/jvondungen]


