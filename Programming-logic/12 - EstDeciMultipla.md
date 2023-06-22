# Estrutura de Decisão Múltipla

1. Introdução

    - Há situações em que uma mesma variável pode gerar condições múltiplas.

        - A mesma variável pode levar a mais de dois caminhos diferentes, dependendo de seu conteúdo.
        - É como se fosse um "menu" de opções.

2. Sintaxe em pseudocódigo

    escolha (variável)
        caso <valor 1> <lista de comandos 1>
        caso <valor 2> <lista de comandos 2>
        caso <valor 3> <lista de comandos 3>
        ...
        caso <valor N> <lista de comandos N>
        outrocaso <lista de comandos padrão>
    fimescolha

3. Exemplo

    - Desenvolva um programa que, dependendo do valor(número inteiro) digitado pelo usuário, deve imprimir na tela o dia da semana correspondente àquele número:

        . 1 = domingo;
        . 2 = segunda-feira;
        . 3 = terça-feira;
        . etc...
    
        Algoritmo "diaDaSemana"
            Var num: inteiro
        Inicio
            escreval("Informe um número de 1 a 7: ")
            leia(num)
            escolha(num)
                caso 1 escreval("Domingo")
                caso 2 escreval("Segunda-feira)
                caso 3 escreval("Terça-feira)
                caso 4 escreval("Quarta-feira)
                caso 5 escreval("Quinta-feira)
                caso 6 escreval("Sexta-feira)
                caso 7 escreval("Sábado")
                outrocaso escreval("Opção inválida!")
            fimescolha
        Fimalgoritmo
