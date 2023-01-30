# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./screenshots/Screenshot%202023-01-30%20224324.png)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learnt the core basics of CSS Grid and how to apply them in complex website layouts including how to create Grid Template Areas for a webpage. I also used the opportunity to how to fix a media query for Grid views in Mobile versions.

To see how you can add code snippets, see below:

```html
<div class="card card--bg-purple">
      <header class="card__header">
        <img src="./images/image-daniel.jpg" class="card__img" alt="">
        <div>
          <h3>Daniel Clifford</h3>
          <p>Verified Graduate</p>
        </div>
      </header>
      <p class="card__lead">
        I received a job offer mid-course, and the subjects I learned were current, if not more so,
        in the company I joined. I honestly feel I got every penny’s worth.
      </p>
      <p class="card__quote">
        “ I was an EMT for many years before I joined the bootcamp. I’ve been looking to make a
        transition and have heard some people who had an amazing experience here. I signed up
        for the free intro course and found it incredibly fun! I enrolled shortly thereafter.
        The next 12 weeks was the best - and most grueling - time of my life. Since completing
        the course, I’ve successfully switched careers, working as a Software Engineer at a VR startup. ”
      </p>
    </div>
```
```css
.container {
    max-width: 1440px;
    margin: 100px auto;
    padding: 20px;
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
}
```

### Continued development

- CSS Grid
- CSS Flexbox
- media queries
## Author

- Frontend Mentor - [@SamuelIbanga5](https://www.frontendmentor.io/profile/SamuelIbanga5)
- Twitter - [@Ibangajnr10](https://www.twitter.com/Ibangajnr10)
