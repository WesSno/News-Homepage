# Frontend Mentor - News homepage solution

This is my solution to the [News homepage challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/news-homepage-H6SWTa1MFl). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

### The challenge

Users are be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot/new-homepage_screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Pure CSS state management (checkbox hack)

### What I learned

This project helped me better understand how to manage UI state using pure CSS, especially for interactive components like a mobile navigation menu.

Key things I learned include:

- The difference between the CSS sibling selectors + (adjacent sibling) and ~ (general sibling), and when to use each.

- How to prevent background scrolling when a sidebar menu is open by restructuring the DOM and controlling overflow

Example of CSS-only state handling used in this project::

```css
#menu-toggle:checked ~ .page .nav-menu {
  right: 0;
}

#menu-toggle:checked ~ .page {
  overflow: hidden;
}
```

This approach allowed me to implement interactivity without JavaScript while still maintaining good UX.

### Continued development

Going forward, I would like to:

- Improve accessibility for the mobile navigation (ARIA attributes, focus management).
- Continue practicing responsive layouts with more complex navigation patterns
- Rebuild the hamburger menu using JavaScript to compare CSS-only vs JS-driven approaches
- Deepen my understanding of CSS architecture and selector strategy

### Useful resources

- [Frontend Mentor - News Homepage challenge](https://www.frontendmentor.io/challenges/news-homepage-H6SWTa1MFl) - Provided a realistic design and requirements for practicing responsive layouts.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

## Acknowledgments

Thanks to the Frontend Mentor community and learning resources that helped clarify CSS layout, selectors, and responsive design concepts.
