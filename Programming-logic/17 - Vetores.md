# Vetores

1. Introdução

    - São estruturas de dados que agrupam diversas informações do MESMO tipo em uma única variável.

    - Variável simples: Apenas um dado é acessível.

    - Agregados homogênios: Vários dados são acessíveis.

    - Podem ser unidimensionais(vetor) ou multidimensionais(matrizes).

2. Vetores

    - É usual manipular conjuntos de valores, em detrimento do dados isolados;

    - Exemplos: notas, preços, produtos, nomes, etc;

    - Para manipular um conjunto de dados do mesmo tipo há uma estrutura de dados denominada vetor.

    - Analogia:

        - Um vetor é um prédio com um andar por apto.

        - Cada posição do vetor é um andar.
    
3. Características dos vetores

    - Conjunto de dados;
    
    - Conjunto referenciado por um único nome;
    
    - Dados controlados por um índice;
    
    - O índice permite referenciar um dado por vez, isoladamente, dentro do conjunto;
    
    - Os elementos do conjunto são dispostos linearmente.
    
    - São "matrizes de uma única linha"
    
    - Também conhecido como: Arranjo, Array, Agregado homogênio unidimensional.

4. Vetores em pseudocódigo

    - São declarados de maneira similar a uma variável comum, porém, adiciona-se o tamanho.

    - Têm um tamanho máximo N.

    - O primeiro elemento encontra-se na posição 1.

    - O último elemento encontra-se na posição N.

5. Sintaxe de declaração de um vetor

    <nome_variavel>: Vetor[<início>...<fim>] de <tipo>

    - Exemplo de criação de um vetor: armazenar até 4(quatro) valores do tipo real.

    Var notas: Vetor[1..4] de real
     _________________________________    
    |Índice   |  1  |  2  |  3  |  4  | 
    |Conteúdo | 10,0| 9,8 | 7,0 | 8,5 | 

    - Sintaxe de acesso a uma posição:

        <nome_do_vetor>[<índice>]
    
    - Exemplos

        . notas[1] <- 10.0;
        . escreva(notas[1]);
        . soma <- soma + notas[i].

6. Exemplo

    - Desenvolver algoritmo para que o usuário seja capaz de armazenas quatro notas bimestrais em um vetor de números reais.

    - Solução 1

        Algoritmo "meu_vetor1"
            Var notas: Vetor[1..4] de real
        Inicio
            escreva("Digite a nota 1: ")
            leia(notas[1])
            escreva("Digite a nota 2: ")
            leia(notas[2])
            escreva("Digite a nota 3: ")
            leia(notas[3])
            escreva("Digite a nota 4: ")
            leia(notas[4])
        Fimalgoritmo

    - Solução 2

        Algoritmo "meu_vetor2"
            Var notas: Vetor[1..4] de real
                    i: inteiro
        Inicio
            Para i de 1 ate 4 passo 1 faca
                escreva("Digite a nota ", i, ": ")
                leia(notas[1])
            Fimpara
        Fimalgoritmo