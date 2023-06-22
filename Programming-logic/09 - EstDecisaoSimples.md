# Estrutura de decisão simples

1. Sintaxe em pseudocódigo:

    se (<expressão lógica>) então
        <sequência de comandos 1>
    fimse

    - Exemplo: Faça um algoritmo que receba dois números, informado pelo usuário, e retorne o maior entre eles.

        Algoritmo "retornaMaior"
            Var num1, num2: inteiro
        Inicio
            escreval("Informe dois números:")
            leia(num1)
            leia(num2)
            se (num1 > num2) então
                escreva(num1)
            fimse
            se (num2 > num1) então
                escreva(num2)
            fimse
        Fimalgoritmo