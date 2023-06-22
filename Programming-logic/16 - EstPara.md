# Estrutura de Repetição Para

1. Introdução

    - É comum repetir um bloco de comandos por um número finito de vezes(pré-determinado).

    - A quantia de repetições é controlada por uma variável: gera-se uma sequência numérica.

    - Por exemplo: imprimir, na tela, os números de 1 a 10:

        - Sequência: 1,2,3,4,5,6,7,8,9,10.

2. Repetição por contagem

    - Estrutura para:

        - Geralmente tem-se uma variável para realizar a contagem, através de uma sŕie numérica: variável(v), valor inicial(i), valor final(f), passo(p).

3. Sintaxe

    para <v> de <i> até <f> passo <p> faca
        <sequência de comandos>
    fimpara

4. Exemplo 1

    - Escreva um algoritmo que seja capaz de imprimir os números de 1 até 10, na tela, invocando a função escreval(), no código, apenas uma vez.

    Algoritmo "contaDe1a10"
        Var cont: inteiro
    Inicio
        para cont de 1 ate 10 faca
            escreval(cont)
        fimpara
    Fimalgoritmo

5. Exemplo 2

    - Escreva um algoritmo que seja capaz de realizar o cálculo do somatório dos números inteiros contidos no intervalo fechado que vai de 1 a 10, utilizando a estrutura para. Ao final, o algoritmo deve exibir uma mensagem contendo o resultado de toda a soma.

    Algoritmo "somaDe1a10"
        Var cont, soma: inteiro
    Inicio
        soma <- 0
        para cont de 1 ate 10 faca
            soma <- soma + cont
        fimpara
        escreval(soma)
    Fimalgoritmo