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
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://github.com/curylo-igor/social-links-profile-main)
- Live Site URL: [Add live site URL here](https://curylo-igor.github.io/social-links-profile-main)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Local Variable Fonts (`@font-face`)

### What I learned

During this project, I learned how to properly set up and use Variable Fonts locally instead of importing multiple static font files. It makes the code cleaner and the site faster.

```css
@font-face {
  font-family: "Inter";
  src: url("./assets/fonts/Inter-VariableFont_slnt,wght.ttf") format("truetype");
  font-weight: 100 900;
  font-style: normal;
  font-display: swap;
}
```

I also learned an amazing trick to perfectly center a component vertically and horizontally using CSS Grid without breaking the footer layout:

```html
body { min-height: 100vh; display: grid; grid-template-rows: 1fr auto 1fr;
justify-items: center; } .profile-card { grid-row: 2; }
```

### AI Collaboration

- Tool: Gemini
- How I used it: I used Gemini as a coding mentor to debug CSS layout issues (specifically vertical centering conflicts with Flexbox and footers) and to understand the implementation of local Variable Fonts. We also worked together to configure GitHub CLI in my terminal for faster deployments.
- What worked well: The step-by-step explanations of why certain CSS behaviors occur (like margin-top: auto acting as a spring) helped me understand the logic behind the fixes, rather than just copying code. Transitioning from Flexbox to CSS Grid for the main layout was a game-changer.

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/curylo-igor)
