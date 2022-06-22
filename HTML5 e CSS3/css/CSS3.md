# Introdução e conceitos básicos do CSS

**1. O que são seletores?**

-são apenas elementos **html**(`<p>,<a>,<h1>`) e dentro de um par de chaves colocamos as declarações, uma declaração é formada por uma props(propriedade) e um valor.

EX: h1 {

    color: blue;
    font-size: 14px
}

**2. Conceitos básicos**
-para importar o css no **html** devemos ir no `<head>` e colocar a tag `<link rel="stylesheet" href="style.css">`

a propriedade `href` servi para indicar o caminha ao nosso arquivo 'CSS'.


## Box model

Possui :four: áreas.


![](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ed/Box-model.svg/1200px-Box-model.svg.png)


- **margem**- São espaçamentos entre os conteúdos.
- **borda**- Elas circundam o padding e o conteúdo e podemos alterar a aparencia delas como largura e cor.
- **padding**- É o espaçamento entre a borda e o conteúdo.
- **conteúdo**- É o que seu bloco representa(texto,imagem ou video)

**3. Id x Classe**

no 'CSS' um **Id** e **class** é nomeado por **#** e **.**

`class`-   **.header** {
    padding: 10px;
}

Um **id** só pode ser usado uma vez na página.

`id`-   **#header** {
    padding: 15px;
}