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

5º Justify Content

Alinhar os itens dentro do container de acordo com a direçção 
pretendida e trata da distribuição de espaçamento entre eles

OBS: Se seus itens ocupam 100% do container, ela não se aplica

Algumas variações:

fles-start: inicio do container
flex-end: final do container
center: ao centro do container
space-between: um espalamento iugal entre os elementos
    Pega o primeiro elemento e coloca muito proximo ao inicio do container e o ultimo ao final
space-around: os espaçamentos do meio são duas vezes maiores que o inicial e final


6º Align-items

Tratamento do alinhamento dos flex itens de acordo com o eixo do container

Alinhamento é diferente quando os itens estão em linhas ou colunas

Permite alinhamento central no eixo vertical

(justify conta)

Tipo:
    Center: alinha no centro
    stretch: padrão, e os flex itens cresçam igualmente
    flex-start: alinhamento dos itens no início
    flex-end: alinhamento para o final
    baseline: de acordo com a linha base da tipografia dos itens
    

    7º Align-content

    tratamento do eixo vertical (linhas do container)

    Precisamos que:
        O container utilize quebra de linhas
        A altura do container seja maior que a soma das linhas dos itens
            (container seja maior que a soma (altura das linhas))
    
    tipos:

    center: alinhamento dos itens ao centro
    stretch: padrão flex itens crescem igualmente
    flex-start: alinhamento dos itens dno inicio
    flex-end: alinhamento dos itens no final
    space-between: cria um espaçamento igual entre os elementos
    space-around: os espaçamentos do meio são duas vezes maiores que o inicial e final

    