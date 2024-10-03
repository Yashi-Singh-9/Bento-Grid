# Frontend Mentor - Bento Grid Solution

[![Netlify Status](https://api.netlify.com/api/v1/badges/4263271b-9608-4310-be47-75f02872f165/deploy-status)](https://app.netlify.com/sites/bento-grid-solution-by-yashi-singh/deploys) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Frontend Mentor](https://img.shields.io/badge/Frontend%20Mentor-fb0?style=for-the-badge&logo=frontendmentor&logoColor=white)
![Last Commit](https://img.shields.io/gitlab/last-commit/Yashi-Singh-9/bento-grid?style=for-the-badge&logo=gitlab&logoColor=white)

This is a solution to the [Bento Grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The Challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size (responsive grid layout)

### Screenshot

#### Desktop Design

![Bento Grid Screenshot](design/desktop-design.jpg)

#### Mobile Design

![Bento Grid Screenshot](design/mobile-design.jpg)

### Links

- Solution URL: [Solution](https://www.frontendmentor.io/solutions/bento-grid-kswn_xvFGG)
- Live Site URL: [Live](https://bento-grid-solution-by-yashi-singh.netlify.app/)

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Flexbox
- Mobile-first workflow

### What I Learned

During this project, I strengthened my understanding of CSS Grid and Flexbox, particularly in building complex, responsive layouts. I also practiced using CSS custom properties to ensure consistency across the design and ease future modifications.

Here’s an example of how I used **CSS Grid** to structure the grid layout:

```css
.bento-grid {
  display: grid;
  grid-template-areas:
    'box1 box2 box2 box3'
    'box1 box2 box2 box3'
    'box4 box5 box6 box3'
    'box4 box7 box8 box8';
  gap: 2rem;
}
```

This project helped me understand how to manage a grid for larger layouts and adapt it for smaller screens using media queries.

### Continued Development

In future projects, I want to focus more on refining my skills in:

- Advanced CSS Grid techniques for even more complex layouts
- Building better animations and transitions to improve the user experience
- Working more with accessibility best practices to ensure the project is inclusive for all users

### Useful Resources

- [CSS Tricks - A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - This helped me understand how to effectively use CSS Grid for complex layouts.
- [MDN Web Docs - Media Queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries) - This resource was incredibly helpful for building responsive layouts.

## Author

- LinkedIn - [Yashi Singh](https://www.linkedin.com/in/yashi-singh-b4143a246)
- Frontend Mentor - [@Yashi-Singh-9](https://www.frontendmentor.io/profile/Yashi-Singh-9)

## Acknowledgments

Thanks to the Frontend Mentor community for their continuous support and helpful resources. This project helped me improve my understanding of layout structures and responsive design.