---
title: Exercícios arvore binaria
date: 01-09-2024
tags:
  - algorithm
  - data_structure
  - pt
index: "[[algorithm]]"
---

#  Exercícios arvore binaria 
## 1 - Considere uma árvore binária de pesquisa, inicialmente vazia, a qual armazena caracteres. Faça a inserção de todas as letras do seu nome completo na mesma sequência da escrita, desprezando os espaços em branco. Considere, também, todas as letras maiúsculas, sem acentuação e a ordenação da árvore de acordo com a ordem alfabética, onde a letra A é o menor valor e a letra Z é o maior. Exemplo: Dilma Vana Rousseff = DILMAVANAROUSSEFF; inserir a letra D, em seguida a letra I, depois a letra L e assim por diante até a inserção da última letra que, no exemplo, é a letra F. Obs: Letras repetidas devem ser inseridas à esquerda. Uma árvore para cada membro da dupla. Alfabeto: A B C D E F G H I J K L M N O P Q R S T U V W X Y Z.

![[diego_btree.png]]
### a) Qual é a altura da árvore?
4
### b)  Dê o resultado de um percurso pós-fixado
```
[G,E,O,I,D]
```
### c) Quem é o sucessor do nó de maior altura (caso existam dois ou mais, considere o menor deles) na árvore?
Não existe.
### e) Quem é o predecessor do quarto nó inserido na árvore?
E.
## 2 - Monte uma árvore binária de pesquisa com a menor altura possível com o seguinte conjunto de dados: { 1, 4, 7, 10, 13, 16, 19, 22, 25, 28, 31, 34, 37, 40, 43 }.
Quebre o array no meio: 
	-  Esquerda: `[1,4,7,10,13,16,19]`
	- Meio: `[22]`
	- Direita: `[25,28,31,34,37,40,43]`
![[ex_2_btree.png]]
## 3 -
## 4 - Quantos nós possui uma árvore estritamente binária, com 12 nós folha? Tente determinar uma fórmula matemática que defina como calcular a quantidade de nós, a partir da quantidade de nós folha.
`N = 2L - 1`
N = 2 * 12 - 1
N = 23
## 5 - Quais são as sequências de nós visitados ao atravessar as árvores abaixo em Pré-ordem, In-ordem e Pós-ordem?

## 6 - Desenhe a árvore binária correspondente às seguintes seqüências em
- Pré-ordem: [1 2 3 4 5 6 7 8 9]
- in-ordem: [3 2 6 5 4 1 7 8 9]
![[ex_6.png]]
## Ex práticos: 
- https://github.com/diegorezm/data_structures_algorithmss/tree/main/code/java/DataStructure/src/lib/btree
# References
- [[Binary tree]]