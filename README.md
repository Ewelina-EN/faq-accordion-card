# Frontend Mentor - FAQ accordion card solution.

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects. I complete the challenge without using JavaScript. On my GitHub profile you can find a second version of this project using JavaScript.

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

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<h1 class="faq_heading">FAQ</h1>
<details class="faq_details">
  <summary class="faq_summary">
    <span class="faq_question"> How many team members can I invite?</span>
  </summary>
</details>
```

```css
proud-of-this-css .faq_details[open] > .faq_summary {
  font-weight: bold;
}

.faq_summary::-webkit-details-marker {
  display: none;
}

.faq_summary:after {
  display: inline-block;
  content: url(./images/icon-arrow-down.svg);
  text-align: right;
  background-repeat: no-repeat;
  background-position: right center;
  padding-bottom: 20px;
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

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Ewelina Niewęgłowska](https://github.com/Ewelina-EN)
