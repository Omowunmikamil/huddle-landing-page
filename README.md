# Frontend Mentor - Fylo landing page with two-column layout solution

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![Mockup](./images/readme-image.png)

### Links

- Solution URL: [Take a view at my solution](https://www.frontendmentor.io/solutions/responsive-landing-page-using-css-flexbox-layout-and-hover-states-Bv_sWaU5Kb)
- Live Site URL: [Visit Live Site](https://omowunmikamil.github.io/fylo-landing-page-with-two-column-layout/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned how to use the grid and flexbox to create a two-column layout. I also learned how to use the position property to position elements on the page.

```html
<h1>Some HTML code I'm proud of</h1>
<section id="hero-section">
      <article class="left-article">
        <h1>All your files in one secure location, accessible anywhere.</h1>
        <p>Fylo stores your most important files in one secure location. Access them wherever you need, share and collaborate with friends, family, and co-workers.</p>
      <article class="input-email">
        <input type="email" id="email" name="email" placeholder="Enter your email...">
        <button>Get Started</button>
      </article>
      </article>
      <article class="right-article">
        <img src="images/illustration-1.svg">
      </article>
</section>

<section id="curve">
</section>
```
```css
.proud-of-this-css {
  color: papayawhip;
}
#hero-section, #body-article {
    display: flex;
    justify-content: space-between;
    align-items: center;
    /*border: 2px solid yellow;*/
    padding: 2em 4em;
    margin: 1em 0;
}

.left-article {
    width: 45%;
    /*border: 2px solid blue;*/
}

.right-article {
    width: 50%;
    /*border: 2px solid red;*/
}

.left-article h1 {
    font-size: 2.3em;
    font-weight: 600;
    line-height: 3.3rem;
    color: hsl(243, 87%, 12%);
}

.left-article p {
    font-size: 1.1em;
    color: hsl(243, 87%, 12%);
    padding-right: 1.4em;
    margin: 1em 0 1.5em;
}

.right-article img {
    width: 100%;
}

.input-email {
    width: 86%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    /*border: 2px solid blue;*/
}

.input-email input {
    width: 57%;
    height: 50px;
    outline: none;
    border: 1px solid black;
    border-radius: 4px;
    padding-top: 2em;
}

input[type="email"] {
    padding: 10px 20px 6px;
    font-size: 14px;
    font-weight: 500;
}

.input-email button {
    width: 40%;
    height: 50px;
    background-color: hsl(224, 93%, 58%);
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

.input-email button:hover {
    background-color: hsl(223, 87%, 63%);
}
#curve {
    width: 100%;
    /*border: 2px solid green;*/
    height: 100px;
    background-image: url(./images/bg-curve-desktop.svg);
    background-repeat: no-repeat;
    background-position: center;
    margin-top: 6em;
}
```

## Author

- Website - [Visit my Portfolio Website](https://omowunmi-kamiludeen.netlify.app/)
- Frontend Mentor - [Omowunmi Kamiludeen](https://www.frontendmentor.io/profile/Omowunmikamil)
- Twitter - [Browser_Nerd](https://www.twitter.com/@Browser_Nerd)

## Acknowledgments

frontend mentor - For providing easy access to this challenge and its resources
