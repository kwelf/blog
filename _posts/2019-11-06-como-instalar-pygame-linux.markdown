---
layout: post
title: Como instalar Pygame no Linux
date: 2019-11-06 17:32:20 +0300
description: Como instalar Pygame no Linux utilizando Ubuntu ou Archlinux # Add post description (optional)
img: pygame.png # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [Python, Pygame]
---
Olá, seja bem vindo ao meu primeiro post no blog. Hoje iremos falar do Pygame e como instalar no seu Linux. Será uma tarefa simples, tenha certeza disso. 
A partir daqui eu irei levar em conta que você já instalou o python em sua distro.
Em primeiro lugar iremos instalar o PiP, acessório essencial para gerenciar instalações de bibliotecas como Pygame dentre outras.
## Instalando o PiP
Para instalar o PiP utilizando o terminal é muito fácil.
No Ubuntu digite:

>sudo apt install python3-pip

Neste caso instalaremos o PiP para seu python versão 3, no Ubuntu.

Diferentemente será no Archlinux conforme vemos:

>sudo pacman -S python-pip

Deste modo, não precisamos especificar o python para a versão 3 pois ele já é por padrão.

## Instalando Pygame através do PiP
Após instalado o PiP, vamos instalar o Pygame.
No Ubuntu digite:

>python3 -m pip install pygame --user

Perceba que estamos instalando a biblioteca pygame apenas para o usuário, pela fato de utilizarmos o argumento "--user".

No Archlinux digite:

>python -m pip install pygame --user

Praticamente idêntico, apenas retirando o 3, pois no arch não precisamos especificar o python 3 pois o mesmo já é por padrão.

## Bônus: Instalando no Pycharm

Entendo que você já tenha o Pycharm instalado em sua distro, desta forma siga os passos:

>Passo 1: Clique em File

>Passo 2: Clique em Settings

>Passo 3: Clique em Project: (Nome do seu projeto)

>Passo 4: Clique em Project Interpreter

>Passo 5: Clique no ícone de + (mais) ao lado direito

>Passo 6: Digite Pygame no campo de busca

>Passo 7: Clique em Install Package e AGUARDE até a tela verde de instalação concluída.

Pronto, após isso feche a janela e seu Pycharm está configurado com o pygame.

![Pycharm Pygame]({{site.baseurl}}/assets/img/pycharm.png)

Obrigado e bons estudos.