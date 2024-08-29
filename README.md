# Recipe Page Project

!Design preview for the Recipe page coding challenge
[https://github.com/olahasan/HTML_AND_CSS_Frontend-Mentor_NEWBIE-Recipe-page/blob/main/design/desktop-design.jpg]

## Overview

This project is a solution to the Recipe Page challenge on Frontend Mentor. Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of Contents

- Overview
  - The Challenge
  - Screenshot
  - Links
- My Process
  - Built With
  - What I Learned
  - Continued Development
  - Useful Resources
- Author

## The Challenge

Your challenge is to build out this recipe page and get it looking as close to the design as possible.

### Screenshot

!Screenshot of the Recipe Page
[https://github.com/olahasan/HTML_AND_CSS_Frontend-Mentor_NEWBIE-Recipe-page/blob/main/design/desktop-preview.jpg]

### Links

- Solution URL: [GitHub Repository] [https://github.com/olahasan/HTML_AND_CSS_Frontend-Mentor_NEWBIE-Recipe-page]
- Live Site URL: [Live Demo] [https://olahasan.github.io/HTML_AND_CSS_Frontend-Mentor_NEWBIE-Recipe-page/]

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I Learned

In this project, I learned how to effectively use CSS variables (:root) for maintaining a consistent color scheme and how to structure a responsive layout using Flexbox and CSS Grid. Here are some code snippets that I am proud of:

<div class="container">
  <div class="menue">
    <div class="image">
      <img decoding="async" src="assets/images/image-omelette.jpeg" alt="pic of main plate" />
    </div>
    <h3 class="young-serif-regular">Simple Omelette Recipe</h3>
    <p>An easy and quick dish, perfect for any meal...</p>
  </div>
</div>

:root {
--Nutmeg: hsl(14, 45%, 36%);
--Dark-Raspberry: hsl(332, 51%, 32%);
--White: hsl(0, 0%, 100%);
--radius: 15px;
}

.all .container .menue {
border-radius: var(--radius);
background-color: var(--White);
padding: 25px;
}

### Continued Development

I plan to continue improving my skills in responsive
design and exploring more advanced CSS techniques. I also aim to enhance the
accessibility of my projects.

### Useful Resources

MDN Web Docs - This helped me
understand the use of CSS variables and Flexbox. Frontend Mentor - Great
platform for practicing front-end development skills.

### Author Frontend Mentor

Frontend Mentor: @olahasan
GitHub: @olahasan
