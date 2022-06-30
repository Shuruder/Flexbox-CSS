// Display:flex

// Conhecer e aplicar as propriedades do flex container

//Conseguimos aplicar em qualquer tag html

1º - Display flex

Tornar os elementos da tag em flex item
- Fazem com que os elementos de tags como div span etc se tornem elementos flex e mesma coisa seus filhos
- Todo flex item também pode ser um flex container


2º - Flex direction

Propriedade que estabelece os eixos dentro de um container.
- Direcionar os flex items dentro do flex container

- Eixos
    - row (padrõ): direção do texto, esquerda para direita como uma linha
    - row-reverse: O mesmo de cima só que contrário (como um mangá kkk)
    - column: Ordenação em forma de colunas
    - column-reverse: igual o de cima só que contrário


3º - Flex Wreap

Definir a quebra de linha ou como se comporta
Tratativa de vazamentos do container

nowrap
    - Por padrão, não permite a quebra de linha

wrap
    - Permite a quebra de linha assim que houver o vazamento do wrap

Wrap-reverse
    - Mesma lógica do Wrap porem sentido contrário (a linha seguinte vai para cima)


4º - Flex-flow

Atalho para as propriedades flex-dfirection e flex-warp
Não é comum de se usar, já que quando mudamos o flex-direction para column, mantemos o padrão do flex-wrap que é nowrap