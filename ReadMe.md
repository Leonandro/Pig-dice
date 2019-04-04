
# Authors

Leonandro Gurgel.

# Intro

Este projeto cria um jogo baseado no já famoso Pig Dice. Ele é feito para 2 jogadores onde o primeiro jogador 
é o usuário e o segundo jogador é a inteligência artificial desenvolvida para o projeto. 



# Compiling and running 

Abra o terminal, entre no diretório do projeto, realize os seguintes comandos.

1. `cd src`: Entra no diretório dos códigos cpp do projeto.
2. `g++ -std=c++11 main.cpp game.cpp -o executavel`: Compila os arquivos do projeto e gera um executável.
3. `./executavel`: Executa o jogo.


# How to play

O jogo é por turnos, quem alcançar 100 pontos gerais primeiro, vence.
O usuário sempre começa, ele tem 2 opções: rolar o dado ou segurar.
Caso ele role e tire um número diferente de 1, a pontuação do dado é somada a pontuação do turno atual.
Caso ele role o dado e tire 1, ele perde toda a pontuação daquela rodada (PIGGY) e a vez é passada para o oponente.
Caso ele segure, a pontuação do turno é somada a sua pontuação geral e a vez é passada para o oponente.



