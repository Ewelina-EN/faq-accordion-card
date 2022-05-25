# Frontend Mentor - FAQ accordion card solution.

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects. I completed the challenge without using JavaScript. On my GitHub profile you can find a second version of this project using JavaScript.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked

### Screenshot

![Design preview for the FAQ accordion card coding challenge](./design/desktop-preview.jpg)

### Links

- Solution URL: [GitHub](https://github.com/Ewelina-EN/faq-accordion-card-withoutjs)
- Live Site URL: [FAQ Accordion Card without JavaScript](https://ewelina-en.github.io/faq-accordion-card-withoutjs/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

For the first time I used an HTML details and summary element:

```html
<details class="faq_details">
  <summary class="faq_summary">
    <span class="faq_question"> How many team members can I invite?</span>
  </summary>
</details>
```

and learned that the selector details[open] can be used to style the element which is open:

```css
.faq_details[open] > .faq_summary {
  font-weight: bold;
}

details[open] .faq_summary:after {
  display: inline-block;
  width: 18px;
  padding-bottom: 10px;
  content: "";
  background-image: url(./images/icon-arrow-down.svg);
  background-repeat: no-repeat;
  background-position: center right;
  transform: scaleY(-1);
}
```

### Continued development

In future project I want to focus on optimize my CSS code. For me, it was an interesting experience to create a project without using JavaScript.

## Author

- Website - [Ewelina Niewęgłowska](https://github.com/Ewelina-EN)
