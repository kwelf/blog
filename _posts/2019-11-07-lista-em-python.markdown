---
layout: post
title: Listas em Python
date: 2019-11-07 16:32:20 +0300
description: Aprendendo a fazer listas em python # Add post description (optional)
img: python.png # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [Python, Listas]
---
Fazer listas em python é muito simples, pois diferente de outras linguagens com sintaxe mais complexas o python nos facilita demais.
Não precisamos definir o tipo da lista pois o python recebe qualquer tipo, por exemplo podemos colocar integer e String numa mesma lista.

## Introdução
Temos que entender que toda lista guarda espaços na memória, definidos pelo usuário ou pelo uso. Desta forma, tais espaços são tratados como índices. 
Veja o exemplo a seguir:
>nome = [‘Carlos’, ‘Fabio’, ‘Marcos’]

Perceba que esta lista contém 3 elementos. Tais elementos são contados como índices, tendo como partida o número 0. Portanto, para acessarmos a lista através dos índices deveremos utilizarmos assim:
>nome[índice]

Então, se por exemplo queremos imprimir na tela o primeiro nome da lista, que neste caso é Carlos, deveremos utilizar assim:
>print(nome[0])

## Lista infinita
Para criarmos uma lista infinita, ou seja, uma lista que comporte vários elementos sem uma definição de limite, devemos primeiro acrescentar a criação dela conforme vemos a seguir:
>nome = []

Desta forma, criamos portanto uma nova lista chamada com a variável nome, e dentro dela podemos adicionar quantos itens quiser.
Para adicionar itens é muito simples, utilizamos o método append, conforme vemos a seguir:
>nome.append(‘Carlos’)

Desta forma, o nome string Carlos estará no índice 0 e nossa lista ficará assim:
>[‘Carlos’]

Ao adicionar outro elemento como por exemplo:
>nome.append(‘Fabio’)

Nossa lista deverá ficar assim:
>[‘Carlos’, ‘Fabio’]

Portanto, a cada uso do append os itens/elementos adicionados ficarão no índice posterior.
Por exemplo, para acessarmos a lista acima e imprimirmos na tela o índice 0 utilizamos assim:
>print(nome[0])

## Conclusão
Concluindo então, o nosso código deverá ficar assim:
>nome = []
<br>nome.append(‘Carlos’)
<br>nome.append(‘Fabio’)
<br>print(nome)

E será impresso na tela nossa lista assim:
>[‘Carlos’, ‘Fabio’]

Por hoje é só pessoal, obrigado.


