# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
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
- See hover states for interactive elements

### Screenshots

![](./screenshots/desktop.jpg)
![](./screenshots/mobile.jpg)

### Links

- Solution URL: https://3-column-preview-card-component-main.glenottley.com/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

Effectively using Kevin Powell's reusable container/row class suggestions to write cleaner CSS/HTML making media queries simpler

```css
.container {
	max-width: 400px;
	margin: 0 auto;
	padding: 3em 0;
	width: 64%;
}

.row {
	display: flex;
	flex-direction: column;
}
```

### Continued development

I am not all that comfortable with setting font sizes in my media queries, not exactly sure when they should be growing/shrinking in order to maintain readability and keep the overall geometry of this layout in particular.

### Useful resources

- [Conquering Responsive Layouts - Kevin Powell](https://courses.kevinpowell.co/courses/conquering-responsive-layouts) - This course taught me how to create reusable classes such as '.container' & '.row'
- [Em vs Rem - Kevin Powell](https://www.youtube.com/watch?v=_-aDOAMmDHI) - Helpful video for those struggling with what font size units to use.

## Author

- Website - [Glen Ottley](https://www.glenottley.com)
- Frontend Mentor - [@glenottley](https://www.frontendmentor.io/profile/glenottley)
- Github - [@glenottley](https://github.com/GlenOttley)
