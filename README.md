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
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page
- View the optimal layout for the interface depending on their device's screen size

### Screenshot

![image](https://github.com/user-attachments/assets/99e6db0c-beab-4be5-bb4a-ceadfb920264)![image](https://github.com/user-attachments/assets/701caf2f-f7f0-4805-83da-2e24f7b35dcc)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [https://t3hj.github.io/social-links-profile-main/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- CSS Custom Properties for color theming
- Modern CSS Reset

### What I learned

Through this project, I reinforced my understanding of creating interactive states and hover effects. I particularly focused on creating smooth transitions and ensuring accessibility with focus states.

Some key code snippets I'm proud of:

```css
/* Using CSS custom properties for consistent theming */
:root {
    --color-green: hsl(75, 94%, 57%);
    --color-white: hsl(0, 0%, 100%);
    --color-grey: hsl(0, 0%, 20%);
    --color-dark-grey: hsl(0, 0%, 12%);
    --color-off-black: hsl(0, 0%, 8%);
}

/* Creating smooth hover transitions */
.social-link {
    transition: all 0.3s ease;
    border: 1px solid transparent;
}

.social-link:hover {
    background-color: transparent;
    color: var(--color-green);
    border-color: var(--color-green);
}
```

### Continued development

In future projects, I would like to focus on:

- Implementing more advanced hover animations
- Exploring CSS Grid for more complex layouts
- Adding dark/light mode theme switching
- Improving accessibility features

### Useful resources

- [CSS Custom Properties Guide](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties) - This helped me understand how to effectively use CSS variables for theming.
- [CSS Transitions](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions) - Great explanation of how to create smooth transitions for hover states.

## Author

- Frontend Mentor - [@t3hj](https://www.frontendmentor.io/profile/t3hj)
- GitHub - [@t3hj](https://github.com/t3hj)
