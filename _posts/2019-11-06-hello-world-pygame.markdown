---
layout: post
title: Hello World no Pygame
date: 2019-11-06 22:32:20 +0300
description: Primeiros passos no Pygame # Add post description (optional)
img: pygame.png # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [Python, Pygame]
---
Dando continuidade ao Pygame hoje falaremos como fazer seu primeiro “Hello World” no Pygame.
Suponho que você já tenha o Pygame instalado.
## Importando a biblioteca Pygame
No Python a maneira de importar biblioteca é usando o import, como vemos:

>import pygame

Ao utilizar este comando você terá toda as funções/métodos do pygame em seu projeto.
A partir de agora iremos analisar os principais comandos.

## Inicializando Pygame
A maneira correta de inicializar o Pygame é usando o comando:
>pygame.init()

Init dispõe de inicialização, desta forma seu “jogo” poderá usar as funções do pygame e distribuir em tela.

![Pycharm Pygame]({{site.baseurl}}/assets/img/hellopygame.png)

Esta é a mensagem que deverá aparecer.

## Definindo o Display
A partir de agora definiremos o display, desta maneira precisamos definir qual a resolução que sua tela/interface terá.
Desta forma utilizamos:
>pygame.display.set_mode(x, y)

As variáveis de x e y definiram x como tamanho vertical e y como tamanho horizontal.
Portanto, se queremos uma tela de proporção 640x480, ficará assim:
>x = 640
y = 480
pygame.display.set_mode(x, y)

Caso você não queira usar variáveis para sua proporção poderá usar assim:
>pygame.display.set_mode((640, 480))

Teremos portanto um display que rapidamente sumirá da tela por não termos um while.

## Manter a tela
Para manter a tela precisamos de um while constante porém utilizando uma função do pygame chamada update.
Desta forma deverá ficar assim
>while 1:
<br>&emsp;pygame.display.update() 

Pronto, desta forma temos o display constantemente na tela, embora não seja possível ainda fechar.
<br>O código inteiro deve ficar assim:
>import pygame
<br>pygame.init()
<br>pygame.display.set_mode((640, 480))
<br>while 1:
<br>&emsp;pygame.display.update()

Por enquanto é só, abraços.
