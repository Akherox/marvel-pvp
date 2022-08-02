# Marvel - PVP 

This is a second practice of mine Frontend studies, a personal challenge to improve mine coding skills building own projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Feed Back](#feed-back)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![](/src/imagens/screenshot.jpg)

### Links

- Code URL: [GitHub](https://github.com/Akherox/marvel-pvp)
- Live Site URL: [GitHub Pages](https://akherox.github.io/marvel-pvp/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Media query - responsive CSS

### What I learned

Selection effects.

```js
const personagens = document.querySelectorAll(".personagem");

personagens.forEach((personagem) => {
  personagem.addEventListener("mouseenter", () => {

    const personagemSelecionado = document.querySelector(".selecionado");
    personagemSelecionado.classList.remove("selecionado");
  });
});
```

```css
.personagem.selecionado{
  border: 2px solid var(--cor-azul-media);
  animation: c-glowing-blue .3s ease-in-out infinite;
  animation-direction: alternate;
}

.personagem:hover{
  animation: c-glowing-blue .3s ease-in-out infinite;
  animation-direction: alternate;
  transform: scale(1.07);
  z-index: 2;
}
```

### Feed Back

I`m going to improve on effects.

### Useful resources

- [Example resource](https://github.com/Akherox/pokedex) - This helped me for it was an old project that i made.

## Author

- Website - [Bryan Bravo](https://www.linkedin.com/in/alex-bravo-008-mk)
- GitHub Profile - [@Akherox](https://github.com/Akherox)
