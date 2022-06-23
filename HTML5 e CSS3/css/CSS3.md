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

## Padding e margin

como atribuir tamanho diferentes para cada lado
:three: formas

1. padding: 10px 5px;(10px se refere a o eixo **y** e o 5px ao eixo **x**)
2. padding 15px 10px 5px 0;(temos um valor para cada lado)
**15px up, 10px right, 5px down, 0 left**
3. padding-**top**: 15px;
   padding-**right**: 10px;
   padding-**bottom**: 5px;
   padding-**left**: 0;
   (Usando as props especifica para cada lado)

## Background

Podemos mudar a cor do fundo,colocar uma imagem,alterar posicionamento.

`background-color: blue;
 background-image: url("bg.png");
 background-position: top;`

## border

:three: valores

- **LARGURA**-pixel, centimetros
- **COR**-#0000ff
- **ESTILO**-Sólida, pontilhada, tracejada

## border-radius

ele permite arredondar os cantos de um elemento.

`border-radius: 10px ou 10%`

## Dimensão e Alinhamento

- Width
- Height
---
- Max-width
- Max-height
---
- Margin
- Text align