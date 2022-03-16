# Huddle landing page with curved sections

![Responsive mockup](design/desktop-preview.jpg)

This is my solution to the [huddle landing page with curved sections challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-curved-sections-5ca5ecd01e82137ec91a50f2). Frontend Mentor is a platform where developers can learn and improve their frontend development skills alongside other developers by implementing solutions to challenges. Each challenge includes designs (both mobile and desktop), assets, and a style guide to get you started. The rest is up to you!

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

The challenge is to build out this huddle landing page with curved sections and get it looking as close to the design as possible.

Users should be able to:

- View the optimal layout depending on their device's screen size.
- See hover states for all interactive elements on the page.
- Receive an error message when the form is submitted if the input field is empty & the email address is not formatted correctly.

I don't have access to the premium Figma/Sketch files, so the design is not pixel perfect.

### Screenshots

<details>
  <summary>Desktop design</summary>

  ![Screenshot of desktop view](design/desktop-design.jpg)
</details>

<details>
  <summary>Active states</summary>

  ![Screenshot of desktop view with active states](design/active-states.jpg)
</details>

<details>
  <summary>Mobile design</summary>

  ![Screenshot of mobile view](design/mobile-design.jpg)
</details>

### Links

- [Live Site URL](https://pavel-frontend-mentor-projects.github.io/huddle-landing-page-with-curved-sections/)
- [Solution URL](https://www.frontendmentor.io/solutions/huddle-landing-page-with-curved-sections-Es6A-XnWH)

## My process

### Built with

- Semantic HTML5 markup
- SCSS
- Flexbox
- Mobile-first workflow

### What I learned

I found a new accessibility-friendly way to hide content using the following snippet.

```css
.visually-hidden {
  clip: rect(1px, 1px, 1px, 1px);
  clip-path: inset(50%);
  height: 1px;
  width: 1px;
  margin: -1px;
  padding: 0;
  white-space: nowrap;
  overflow: hidden;
  position: absolute;
}
```

### Useful resources

1. [Perfect Pixel](https://chrome.google.com/webstore/detail/perfectpixel-by-welldonec/dkaagdgjmgdmbnecmcefdhjekcoceebi) - Awesome Chrome extension that helps you to match the pixels of the provided design.

## Author

- Frontend Mentor - [@iPavelGeorgiev](https://www.frontendmentor.io/profile/iPavelGeorgiev)
- LinkedIn - [@iPavelGeorgiev](https://www.linkedin.com/in/ipavelgeorgiev/)

## Acknowledgments

A big thank you to anyone providing feedback on my [solution](https://www.frontendmentor.io/solutions/huddle-landing-page-with-curved-sections-Es6A-XnWH). It definitely helps to find new ways to code and find easier solutions!