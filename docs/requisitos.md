# Arquitetura

* As funções relacionadas ao gerenciamento das casas do jogo da velha ficarão no módulo **jogovelha.py**.

* O estado de cada casa do jogo será representada por uma string: "." para casa vazia;. "X" para casa ocupada pelo 1º jogador; "O" para casa ocupada pelo 2º jogador

* A ficarão inicializar() retornará uma lista de 3x3, onde cada posição conterá uma string para indicar o estado de uma casa do jogo. A função retornará todas as casas inicialmente vazias.