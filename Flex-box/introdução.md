# Flex box

## O que é flexbox

O **Flexbox** é um conceito do **CSS3** que visa organizar os elementos de uma página HTML dentro de seus containers de forma dinâmica. Ou seja, independente das suas dimensões eles sempre manterão um layout flexível dentro do seu elemento pai, reorganizando-se e acordo com a necessidade.

possui um método que pode oferecer distribuição de espaço entre itens em uma interface e recusos de alinhamento.

## flex Container

Ela é a tag que envolve os itens, ou sejá é a tag que possui itens filhos.

aplicando a propriedade `display: flex`. transforma todos os itens filhos em flex itens.
:exclamation:**obs:essa inicialização de container pode ser utilizada para qualquer tipo de tag**

#### propriedades relacionadas:

- display:*é o inicializador do container*.   
- flex-direction:*fazer o direcionamentos dos items, sejá em linha o coluna*.
- flex-wrap:*vai se aplicar para quebra de linha ou não*.
- flex-flow:*é uma abreviação para o direction e o wrap*.
- justify-content-vai alinhar os itens do conteiner de acordo com sua direção.
- align-items- *vai alinhar esses itens de acordo com o seu eixo*.
- align-content-*vai alinhar as linha desse conteiner*.

## flex item

são os elementos filhos diretos do Flex Container.E também podem se tornar Flex Container.

#### propriedades relacionadas:

- flex-grow:*defini um fator de crescimento*.
- flex-basis:*defini o valor inicial desse item antes da distribuição do espaço restante do conteiner*.
- flex-shrink:*defini a capacidade de redução*.
- flex:*é uma abreviação dos elementos grow,basis,shrink*.
- order:*relacionada a ordem de distribuição e listagem desses itens*.
- align-self:*vai definir o alinhamento de um item expecifico desse conteiner*.

