# Estrutura de Decisão Composta

1. Sintaxe em pseudocódigo

    se (<expressão lógica>) então
       <sequência de comandos 1>
    senao
       <sequência de comandos 2>
    fimse

    - Exemplo: Faça um algoritmo que receba dois números, informados pelo usuário, e retorne o maior entre eles.

        Algoritmo "retornaMaior"
            Var num1, num2: inteiro
        Inicio
            escreval("Informe dois números: ")
            leia(num1, num2)
            se (num1 > num2) então
                escreval(num1)
            senao
                escreval(num2)
            fimse
        Fimalgoritmo