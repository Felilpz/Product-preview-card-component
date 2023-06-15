# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements


### Links

- Solution URL: (https://your-solution-url.com)
- Live Site URL: (https://felilpz.github.io/product-previeww-card-component)

## My process

### Built with

- FlexBox
- Bootstrap (na primeira versão! Mas refiz com FlexBox)


### What I learned

- Aprendi um pouco mais sobre flexbox
- Fontes personalizadas
- Estilização do layout e conteúdo
- Responsividade (media)
- Pseudo-classes

To see how you can add code snippets, see below:

```css
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 1rem;
```

```css
    @font-face {
    font-family: "First-Font";
    src: url(../font/Braveold-Bold.otf);
}
```

```css
    body {
    background-color: hsl(30, 38%, 92%);
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}
```

```css
    @media only screen and (max-width: 576px) {
    .card {
        margin-top: 1rem;
        margin-bottom: 1rem;
        flex-direction: column;
    }
}
```

```css
    .conteudo #btn:hover {
    background-color: hsl(157, 51%, 11%);
    transition: .5s;
}
```
## Author

- Website - (https://www.github.com/Felilpz)
- Frontend Mentor - (https://www.frontendmentor.io/profile/Felilpz)