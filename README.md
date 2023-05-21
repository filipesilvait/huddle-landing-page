# Frontend Mentor - Huddle landing page with alternating feature blocks solution

Esta é uma solução para o desafio [Huddle landing page with alternating feature blocks challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-alternating-feature-blocks-5ca5f5981e82137ec91a5100). Frontend Mentor challenges ajuda a melhorar as habilidades praticas com o código, através da criação de projetos realistas.

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

Os usuários devem ser capazes de:

- Visualizar o layout ideal depedendo do tamanho da tela do dispositivo
- Vizualizar os elementos interativos.

### Screenshot

<img src="./assets/design/screenshot.jpg" style="zoom:35%;" />

### Links

- URL do projeto: https://filipesilvait.github.io/huddle-landing-page/

## My process

### Built with

- HTML5 semântico
- CSS
- Flexbox

### What I learned

Aprendi como fazer uma página responsiva.

```css
@media screen and (max-width: 768px) {
    body {
        text-align: center;
    }

    nav.flex {
        flex-direction: row;
    }

    .header-img {
        margin-top: 53px;
        margin-left: 0;
        width: 100%;
    }

    .flex {
        flex-direction: column;
    }

    .box-reverse-mobile {
        flex-direction: column-reverse;
    }

    footer ul {
        padding: 0;
        width: 100%;
    }

    footer .p {
        text-align: center;
    }
}
```
### Continued development

Continuar a aprender HTML e CSS e mais pra frente começar a aprender JavaScript.

### Useful resources

- [flex - CSS: Cascading Style Sheets | MDN (mozilla.org)](https://developer.mozilla.org/en-US/docs/Web/CSS/flex) - Me ajudou com o uso do Flex.

## Author

- Linkedin - https://www.linkedin.com/in/filipesilvait/
- Twitter - [@filipesilvait](https://twitter.com/filipesilvait)

## Acknowledgments

[Florin Pop | LinkedIn](https://www.linkedin.com/in/florinpop17/) me ajudou.
