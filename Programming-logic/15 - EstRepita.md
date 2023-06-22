# Estrutura de Repetição Repita

1. Introdução

    - A estrutura de repetição REPITA é similar a estrutura do comando enquanto. Porém a análise da condição é invertida.

    - Repetição por condição

        - Bloco de comandos é executaado repetidas vezes até que a condição seja verdadeira (enquanto for falsa)

2. Repetição por condição

    - O teste lógico é feito ao final do bloco de comandos definido pela estrutura.
    - O bloco de comandos é executado ao menos uma vez, obrigatoriamente.

3. Sintaxe

    repita
        <sequencia de comandos>
    ate(<expressão lógica>)

4. Exemplo 1

    - Em um formulário da internet, é preciso garantir que o usuário insita um valor maior ou igual a zero. Caso contrário, o dado é considerado inválido e o usuário deve inserir novamente um dado até satisfazer a condição. Assim sendo, desenvolva um algoritmo que simule tal validação.

    Algoritmo "maiorQueZero"
        Var val: inteiro
    Inicio
        repita
            escreval("insira um valor: ")
            leia(val)
        ate(val >= 0)
        escreval("Valor validado: ", val)
    Fimalgoritmo

5. Exemplo 2

    - Escreva um algoritmo que seja capar de imprimir os números de 1 até 10, na tela, invocando a função escreval(), no código, apenas uma vez.

    Algoritmo "contaDe1a10"
        Var cont: inteiro
    Inicio
        cont <- 1
        repita
            escreval(cont)
            cont <- cont + 1
        ate (cont > 10)
    Fimalgoritmo