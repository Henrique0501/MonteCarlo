# Ajuste por Método Alternativo
Trata-se de um software capaz de realizar ajuste de um gráfico a partir de um método alternativo.

O método consiste em gerar eventos aleatórios que sirvam de estimativas para os parâmetros de ajuste. Cada vez que a estimativa gerada produz um quiquadrado menor que a estimativa anterior, é registrada a interação. Quando o algoritmo é finalizado, a lista de todas as interações pode ser utilizada para inferir se há correlação entre os parâmetros de ajuste. A melhor estimativa será aquela que proporciona o menor valor para o quiquadrado.

Este software foi desenvolvido por mim em 2021. Na época eu acreditava que esse algoritmo contemplava o método de Monte Carlo. Hoje compreendo que consiste apenas em um método de tentativa e erro, já que não trata de nenhuma análise probabilística.

Link para o vídeo onde comento sobre o código e aplicabilidade: https://www.youtube.com/watch?v=fVOXle4JJaU
