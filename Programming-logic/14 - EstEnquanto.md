# Estrutura de Repetição Enquanto

1. Introdução

    - Assim como nas estruturas de seleção, nas estruturas de repetição o bloco de comandos é executado repetidas vezes enquanto a condição for verdadeira.

    - Imagine a seguinte situação de um problema: em um formulário da internet, é preciso garantir que o usuário insira um valor maior ou igual a zero. Casa contrário, o dado é considerado inválido e o usuário deve inserir novamente um dado até satisfazer a condição.

2. Repetição por condição

    - Estrutura enquanto:

        - Geralemente tem-se uma condição que é satisfeita de maneira imprevisível.
        - O número de repetições é controlado por uma expressão lógica/relaciona.

3. Sintaxe

    enquanto (<expressão lógica>) faca
        <sequnência de comandos>
    fimenquanto

4. Exemplo 1

    - Em um formulário da internet, é preciso garantir que o usuário insira um valor maior ou igual a zero. Caso contrário, o dado é considerado inválido e o usuário deve inserir novamente um dado até satisfaze a condição. Assim sendo, desenvolva um algoritmo que simula tal validação.

    Algoritmo "maiorQueZero"
        Var val: inteiro
    Inicio
        val <- -1
        eornquanto (val < 0) faca
            escreval("insira um valor: ")
            leia(val)
        fimenquanto
        escreval("Valor validado: ", val)
    Fimalgoritmo

5. Exemplo 2

    - Escreva um algoritmo que seja capaz de imprimir os números de 1 até 10, na tela, invocando a função escreval(), no código, apenas uma vez.

    Algoritmo "contaDe1a10"
        Var cont: inteiro
    Inicio
        cont <- 1
        enquanto (cont <= 10) faca
            escreval(cont)
            cont <- cont + 1
        fimenquanto
    Fimalgoritmo