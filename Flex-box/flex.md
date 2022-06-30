# flex

Ela servi para tratar a distribuição de tamanho dos itens, ele irar crescer de acordo com o conteúdo que está no item.

## flex-grow

Define a proporcionalidade de crescimentos dos itens, respeitando o tamnanho de seus conteúdos internos.

**OBS:** não irá funcionar caso tenhamos adicionado `justify-content` ao nosso flex container.

## flex-basis

é a propriedade que estabelece o tamanho inicial dos item antes das distribuição de espaço restante dentro dele,usando como base o conteúdo interno.

**Valores**

auto: caso o item não tenha tamanho.

px,%,em:sãovalores exatos previamente definidos.

0: terá relação com a definição do flex-grow

## flex-shrink

é a propriedade que estabelecer a capacidade de redução ou compressão do tamanho de um item.

