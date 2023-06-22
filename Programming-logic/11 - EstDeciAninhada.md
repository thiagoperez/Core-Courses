# Estrutura de Decisão Aninhada

1. Introdução

    - Pode-se comportor estruturas condicionais mais complexas

        - Coloca-se um "se-entoo-senao" dentro do outro, de cacordo com a lógica.
        - Pode-se utilizar estruturas condicionas simples, compostas e múltiplas.
        - Criam-se vários níveis de decisões em que a decisão mais interna só será conferida caso a decisão mais externa tenha resultado verdadeiro.

2. Sintaxe em pseudocódigo

    se(<expressão lógica 1>) então
        se(<expressaõ lógica 2>) então
            <sequência de comandos 1>
        fimse
    senão
        se(<expressão lógica 3>) então
            <sequência de comandos 2>
        fimse
    fimse

3. Exemplo

    - Faça um algoritmo que receba a nota final de um aluno.
        
        - Retorne "aprovado" caso a nota seja maior ou igual a 7.
        - "Recuperação" se a média for maior ou igual a 4, porém meno que 7.
        - Imprima "reprovado" caso a média seja menor que 4.

        Algoritmo "notas"
            Var nota: real
        Inicio
                escreval("Insira a nota final: ")
                leia(nota)
            se (nota >= 7.0) então
                escreval("Aprovado!")
            senão
                se (nota >= 4.0) então
                    escreval("Ficou de exame.")
                senão
                    escreval("Reprovado.")
                fimse
            fimse
        Fimalgoritmo